# Microservices Management System

This repository demonstrates a microservices management system developed in Go. The system includes service registration and discovery, RPC, distributed configuration center, microservice gateway, circuit breaker, rate limiting, load balancing, and unified authentication and authorization.

## Prerequisites

- Go installed (version >= 1.16)
- Docker installed (for running the services and databases)
- Make installed (for running make commands)
- Protobuf compiler (protoc) installed

# Features
Service Registration and Discovery
The system uses a service registry (e.g., Consul, Etcd) to register and discover services dynamically.

## RPC
gRPC is used for communication between microservices, providing high performance and reliability.

## Distributed Configuration Center
A distributed configuration center (e.g., Apollo, Nacos) is used to manage configuration for all services centrally.

## Microservice Gateway
The gateway service uses Gin to route and proxy requests to the appropriate microservices, providing a unified entry point.

## Circuit Breaker, Rate Limiting, and Load Balancing
The system incorporates circuit breaker patterns, rate limiting, and load balancing to ensure resilience and scalability.

## Unified Authentication and Authorization
The authentication service handles user authentication and authorization, ensuring secure access to services.

