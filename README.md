# 🚌 Bus Ticket Reservation Service

> A production-ready, thread-safe REST API for managing inter-city bus ticket reservations
Built with core Java servlets, featuring concurrent seat booking, route-based pricing, and in-memory data management. Deployable as WAR file to any standard servlet container (Tomcat/Jetty).

[![Java](https://img.shields.io/badge/Java-17-orange)]()
[![Package](https://img.shields.io/badge/Package-WAR-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

## Overview

Enterprise-grade bus reservation system supporting concurrent bookings across multiple routes (A ↔ B ↔ C ↔ D) with 40-seat capacity management. Implements advanced concurrency controls using `ReentrantReadWriteLock` and `ConcurrentHashMap` for race-condition-free seat allocation.

### Key Features
- ✅ Thread-safe concurrent booking
- ✅ Route-based dynamic pricing
- ✅ RESTful API design
- ✅ Zero-dependency core (pure Java Servlets)
- ✅ Comprehensive unit & integration tests
- ✅ WAR deployment ready
