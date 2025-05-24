# 🗄️ Database References

This repository provides essential references and configuration steps to set up and manage a **PostgreSQL** database instance using **Amazon RDS**.

---

## 🚀 Getting Started with AWS RDS

Follow the tutorial below to create an Amazon RDS PostgreSQL instance up to the database creation phase:

- 🎥 [AWS RDS Setup Tutorial (YouTube)](https://www.youtube.com/watch?v=0A-5ITILrMA)

---

## 🛠️ Database Configuration Summary

| Property             | Value                                      |
|----------------------|--------------------------------------------|
| **DB Engine**         | PostgreSQL 13.6                            |
| **DB Identifier**     | `PostgreSQL-13-6-R1-Server`                |
| **Database Name**     | `AppDB`                                    |
| **Master Username**   | `postgres`                                 |
| **Master Password**   | 🔒 **Stored securely (not included here)** |
| **Hosting Service**   | Amazon RDS (us-east-1 region)              |

---

## 🔗 Useful AWS Console Links

- 📊 [AWS RDS Dashboard](https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#databases:)

- 🧩 [PostgreSQL RDS Instance](https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#database:id=postgresql-13-6-r1-prayer-server;is-cluster=false)

---

## 📘 Documentation & Guides

- 📄 [AWS RDS PostgreSQL Documentation](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_PostgreSQL.html)
- 🔐 [AWS Secrets Manager for DB Credentials](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
- 🧪 [Connecting to a PostgreSQL DB Instance](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToPostgreSQLInstance.html)

---

## 🧠 Best Practices

- Use **parameter groups** to fine-tune performance.
- Enable **automated backups** and **multi-AZ** for high availability.
- Use **IAM authentication** where possible.
- Store credentials securely using **environment variables** or **Secrets Manager**.
- Regularly **monitor logs** and performance metrics via CloudWatch.

---
