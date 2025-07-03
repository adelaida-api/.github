# Adelaida

**Adelaida** is an **open API platform** designed to unify RESTful API access and management for both developers and system administrators. It allows developers to browse, test, and integrate APIs seamlessly while giving administrators full control over API exposure, usage analytics, and access control.

## 🚀 Features

### For Developers
- **Explore Available APIs** with detailed Swagger/OpenAPI documentation.
- **Interactive Online Testing** via web interface.
- **SDK Integration** to quickly connect APIs to your applications.
- **API Access Control**: Apply for and manage API usage permissions.

### For Administrators
- **API Management**: Register and publish new APIs.
- **Traffic Monitoring**: Real-time usage statistics and call frequency.
- **Access Control**: Limit access to authorised users.
- **Rate Limiting**: Prevent abuse with traffic policies.
- **Security Measures**: Protect APIs from attacks.
- **Gateway-Based Routing**: Handle API routing and filtering efficiently.

Unlike OpenAPI or Swagger, which focus on documentation, Adelaida provides a full-featured platform to support secure, scalable, and controlled API usage.

---

## 📦 Tech Stack

### Frontend
- React
- TypeScript
- Ant Design Pro
- Umi
- **OpenAPI code generation** for automatic client code scaffolding

### Backend
- Java 17
- Spring Boot
- MySQL 8
- MyBatis Plus
- Swagger / OpenAPI documentation generation
- Spring Cloud Gateway for:
  - Routing
  - Rate limiting
  - Logging
- Apache Dubbo for distributed RPC

---

## 📚 Use Cases

1. **Frontend Teams** needing stable and structured access to backend services.
2. **Third-party Systems** integrating and reusing existing functionality securely.
3. **Enterprise Developers** looking for a managed API environment with access control and metering.

---

## 🛡️ Security & Governance

- Fine-grained permission control per user and per API
- Configurable rate limiting to prevent misuse
- Audit logs for traceability
- API token authentication and access keys

---

## 📄 License

GPL-2.0

---

## 🤝 Contributions

Contributions are welcome! Please open an issue or pull request to get involved.
