# SerilogSuppressLoggingExample
Example of dynamical suppressing of Serilog log events.

# Update

Don't use this as is, better rework your code to accept Serilog's `ILogger` as dependency and suppress only on this particular logger level instead of relying on ambient context.
