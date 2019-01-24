# Simply PID

Simply PID is a very simple [PID controller](https://en.wikipedia.org/wiki/PID_controller) implementation in Java. It is MIT licensed: it can be included in any project with no restriction.

## Usage 

To get started, simply add the `SimplyPID.java` Java source file to your project.

An example is included: `SimplyPIDExample`.

This is the basic usage:
1. Construct the PID object with a Kp, Ki, Kd and a set point.
2. Call the `getOutput` method to compute the PID output. This is usually performed at a steady rate.
3. At any time, you can change some parameters: Kp, Ki, Kd, the set point or minimum/maximum output bounds.

## Methods description

The methods are all described in the source file using the standard Javadoc format.
