## Day 02 ##
## Activities ## 
1. Studying about the principles of 12 factor App 

# Learnings # 
The main goal of the Twelve-Factor App is to provide a standardized approach to developing applications that can run in a cloud-native environment while remaining flexible, robust, and easy to manage.
The twelve-factor app methodology provides us with a set of best practices for building a modern cloud-native application that meets these requirements:

Codebase
:-One codebase is tracked in version control.
:-Multiple deployments share the same codebase.

Dependencies
:-Explicitly declare and isolate dependencies.
:-Avoid relying on system-wide packages.

Config
:-Store configuration in the environment.
:-Separate configuration from code

Backing Services
:-Treat backing services (databases, caches) as attached resources.
:-Access them via environment variables.

Build, Release, Run
:-Strictly separate build, release, and run stages.
:-Keep builds and releases immutable

Processes
:-Execute the app as stateless processes.
:-Store shared state in databases or external services

Port Binding
:-Export services via port binding.
:-Keep the app self-contained.

Concurrency
:-Scale out via the process model.
:-Enable horizontal scaling.

Disposability
:-Maximize robustness with fast startup and graceful shutdown.
:-Aim for quick startup and graceful handling of process failures.

Dev/Prod Parity
:-Keep development, staging, and production environments as similar as possible.
:-Minimize differences to reduce bugs.

Logs
:-Treat logs as event streams.
:-Stream logs to a centralized location for analysis.

Admin Processes
:-Run admin/management tasks as one-off processes.
:-Avoid mixing them with the main application code
