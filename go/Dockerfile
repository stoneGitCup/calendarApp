# Start from a base image with Go installed
FROM golang:alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the Go files to the container
COPY . .

# Build the Go app
RUN go build -o main .

# Expose port 8080 to the outside world
EXPOSE 8080

# Run the executable
CMD ["/app/main"]