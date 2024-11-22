# HospConnect

HospConnect is a modular **hospital management system** designed to simplify hospital operations and enhance the user experience for doctors, patients, and administrators. This repository acts as the **central hub** for managing and navigating the various microservices that make up the system.

---

## **Description**

HospConnect enables seamless integration between different hospital functionalities such as:
- User management
- Appointment scheduling
- Payment processing
- Notifications for reminders and updates

Each microservice operates independently, making it scalable, reliable, and easy to maintain.

---

## **Technology Stack**

The HospConnect project utilizes the following technologies:

### Backend:
- **Programming Language:** Go (Golang)
- **Frameworks/Libraries:** Mux, gRPC, Gorilla WebSocket
- **Database:** PostgreSQL, Redis
- **API Gateway:** Nginx
- **Messaging:** Apache Kafka (for event-driven architecture)
- **Authentication:** JWT

### Infrastructure:
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **CI/CD:** GitHub Actions
- **Cloud Hosting:** AWS/GCP/Azure
- **Logging** logrus, lumberjack
- **Monitoring:** Prometheus, Grafana

---

## **Microservices**

The HospConnect project consists of the following microservices:

1. **[User Management Service](https://github.com/NUHMANUDHEENT/hosp-connect-api-gateway.git)**
   - Handles user authentication, authorization, and role-based access control.(Admin, Doctor, Patient)

2. **[Appointment Service](https://github.com/NUHMANUDHEENT/hosp-connect-appointment-service.git)**
   - Manages doctor-patient appointment scheduling and token generation.

3. **[Payment Service](https://github.com/NUHMANUDHEENT/hosp-connect-payment-service.git)**
   - Processes payments for appointments and additional treatments.

4. **[Notification Service](https://github.com/NUHMANUDHEENT/hosp-connect-notification-service.git)**
   - Sends reminders, updates, and alerts for appointments, payments, and more.

---

## **How to Clone the Repository**

To set up the central repository and initialize submodules, follow these steps:

1. Clone the central repository:
   ```bash
   git clone https://github.com/your-username/HospConnect.git
