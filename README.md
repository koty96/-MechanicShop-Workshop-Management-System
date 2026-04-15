# MechanicShop — Workshop Management System

A full-stack, production-ready ASP.NET Core application for managing an auto repair workshop. Built with **Clean Architecture**, **CQRS**, **Blazor WebAssembly**, and a complete observability stack — fully containerized with Docker Compose.

## Overview

MechanicShop is a workshop management platform that helps auto repair shops handle their day-to-day operations from customer intake and scheduling to repair tracking, work orders, and invoicing. The system exposes a REST API consumed by a Blazor WebAssembly frontend, with real-time updates powered by SignalR.

---

## Features

- **Customer Management** — Create, view, update, and delete customer records
- **Repair Tasks** — Define and manage available repair services
- **Scheduling** — Assign technicians and book appointments
- **Work Orders** — Track repair status with real-time SignalR updates
- **Invoicing** — Generate PDF invoices per work order (via QuestPDF)
- **Authentication & Authorization** — JWT-based auth with refresh token support and role-based policies
- **API Documentation** — Interactive docs via Swagger UI and Scalar
- **Observability** — Structured logging (Serilog → Seq), distributed tracing (OpenTelemetry → Seq), metrics (Prometheus + Grafana), and health checks

---

## 🚀 Tech Stack

- **Backend:** ASP.NET Core Web API
- **Frontend:** Blazor WebAssembly
- **Architecture:** Clean Architecture + CQRS (MediatR)
- **Validation:** FluentValidation
- **Real-time:** SignalR
- **PDF Generation:** QuestPDF
- **Logging & Monitoring:** Serilog, Seq, OpenTelemetry, Prometheus, Grafana
- **Containerization:** Docker & Docker Compose

---

## 📌 Notes

This project is designed to demonstrate real-world backend architecture and best practices, including scalability, maintainability, and observability.
