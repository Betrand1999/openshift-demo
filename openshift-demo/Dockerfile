# Use an official base image that supports non-root users
FROM busybox

# Create a new non-root user with UID 1001
RUN adduser -u 1001 -D myuser

# Switch to the non-root user
USER myuser

# Command to output "Hello World" and keep the container running
CMD ["/bin/sh", "-c", "echo Hello World && sleep infinity"]
