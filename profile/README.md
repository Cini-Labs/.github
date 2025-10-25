# 💝 Cini - Connecting Ethiopian Hearts Worldwide

<div align="center">

![Cini Logo](https://via.placeholder.com/200x200/D4AF37/FFFFFF?text=Cini)

**A modern dating platform built for the Ethiopian diaspora community**

[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)

</div>

---

## 🌟 About Cini

Cini is a culturally-focused dating application designed to help Ethiopian diaspora members find meaningful connections based on shared values, culture, and traditions. We understand the unique challenges of maintaining cultural identity while living abroad, and we've built a platform that celebrates Ethiopian heritage while embracing modern technology.

### ✨ Key Features

- 🎯 **Cultural Compatibility Matching** - Find partners who share your values and traditions
- 📸 **Photo Verification** - Authentic profiles with up to 6 photos per user
- 💬 **Real-time Messaging** - Connect instantly with WebSocket-powered chat
- 🌍 **Location-based Discovery** - Find matches near you with geospatial search
- 🎉 **Community Events** - Discover and join Ethiopian community gatherings
- 👑 **Premium Features** - Unlimited messaging and advanced filters
- 🔒 **Privacy First** - Your data is secure and never shared

---

## 🏗️ Architecture

Cini is built with a modern, scalable microservices architecture:

### Frontend
- **React Native** with Expo SDK 52
- **Redux Toolkit** for state management
- **Expo Router** for file-based navigation
- **TypeScript** for type safety
- Cross-platform (iOS & Android)

### Backend
- **Django 5.2** REST API
- **PostgreSQL** for data persistence
- **Redis** for caching and Celery broker
- **Celery** for background tasks
- **WebSocket** for real-time messaging
- **Stripe** for payment processing

### Infrastructure
- **AWS ECS Fargate** for containerized services
- **RDS PostgreSQL** for database
- **ElastiCache Redis** for caching
- **S3 + CloudFront** for media delivery
- **Application Load Balancer** for traffic distribution
- **Terraform** for infrastructure as code
- **GitHub Actions** for CI/CD

---

## 📦 Repositories

### [Cini-FrontEnd](https://github.com/Cini-Labs/Cini-FrontEnd)
Mobile application built with React Native and Expo
- Cross-platform iOS and Android app
- Beautiful, intuitive UI with Ethiopian cultural elements
- Redux state management
- Real-time messaging
- Photo upload and management
- Premium subscription flow

### [Cini-BackEnd](https://github.com/Cini-Labs/Cini-BackEnd)
Django REST API powering the Cini platform
- RESTful API with Django REST Framework
- OTP-based authentication
- Profile management and matching algorithms
- Real-time messaging with WebSocket
- Celery for background tasks
- Stripe integration for payments
- S3 integration for media storage

### [Cini-Infrustructure](https://github.com/Cini-Labs/Cini-Infrustructure)
Terraform configuration for AWS infrastructure
- Complete AWS infrastructure as code
- ECS Fargate microservices
- RDS, Redis, S3, CloudFront
- GitHub Actions workflows
- Cost-optimized for development (~$80-95/month)
- Production-ready architecture

### [Cini-Api-Client](https://github.com/Cini-Labs/Cini-Api-Client)
API testing and documentation
- Bruno API collection
- Comprehensive API documentation
- Test scripts and examples

### [Cini-Admin](https://github.com/Cini-Labs/Cini-Admin)
Admin dashboard for platform management
- User management
- Content moderation
- Analytics and insights

---

## 🚀 Tech Stack

<div align="center">

| Layer | Technologies |
|-------|-------------|
| **Mobile** | React Native, Expo, TypeScript, Redux Toolkit |
| **Backend** | Django, DRF, PostgreSQL, Redis, Celery |
| **Infrastructure** | AWS (ECS, RDS, S3, CloudFront), Terraform |
| **DevOps** | Docker, GitHub Actions, AWS ECR |
| **Payments** | Stripe |
| **Storage** | S3, CloudFront CDN |
| **Real-time** | WebSocket, Redis |

</div>

---

## 🎯 Our Mission

**Connecting Ethiopian hearts, preserving culture, building futures.**

We believe that finding love shouldn't mean compromising your cultural identity. Cini helps Ethiopian diaspora members:

- 🤝 Connect with others who understand their cultural background
- 💑 Find partners who share their values and traditions
- 🌍 Stay connected to the Ethiopian community worldwide
- 🎊 Discover local Ethiopian events and gatherings
- 💝 Build meaningful, lasting relationships

---

## 🌈 Why Cini?

### For Users
- **Cultural Understanding** - No need to explain your traditions
- **Verified Profiles** - Real people, authentic connections
- **Privacy Focused** - Your data is secure and protected
- **Community Driven** - Events and gatherings to meet in person
- **Modern Experience** - Beautiful, intuitive mobile app

### For Developers
- **Modern Stack** - Latest technologies and best practices
- **Well Documented** - Comprehensive documentation and cursor rules
- **Clean Architecture** - Microservices, separation of concerns
- **CI/CD Ready** - Automated testing and deployment
- **Scalable** - Built to grow from day one

---

## 📊 Project Stats

- 🎨 **3 Main Repositories** - Frontend, Backend, Infrastructure
- 📱 **Cross-platform** - iOS and Android support
- 🌍 **Cloud-native** - Fully deployed on AWS
- 🔒 **Secure** - HTTPS, encrypted data, private S3
- 💰 **Cost-optimized** - ~$80-95/month for dev environment
- 🚀 **Production-ready** - Scalable architecture

---

## 🛠️ Development

### Prerequisites
- Node.js 18+ (Frontend)
- Python 3.11+ (Backend)
- Docker (Backend)
- AWS CLI (Infrastructure)
- Terraform 1.5+ (Infrastructure)

### Quick Start

#### Frontend
```bash
cd Cini-FrontEnd
npm install
npm start
```

#### Backend
```bash
cd Cini-BackEnd
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

#### Infrastructure
```bash
cd Cini-Infrustructure/terraform
terraform init
terraform plan
terraform apply
```

---

## 🤝 Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help is appreciated.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Standards
- Follow existing code patterns
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed
- Use our `.cursorrules` for AI-assisted development

---

## 📝 Documentation

Each repository includes comprehensive documentation:

- **Frontend**: `.cursorrules` with React Native/Expo patterns
- **Backend**: `.cursorrules` with Django/DRF patterns
- **Infrastructure**: `.cursor/` directory with organized docs
  - `rules.md` - General rules and best practices
  - `architecture.md` - AWS architecture details
  - `terraform-patterns.md` - Terraform patterns and examples
  - `troubleshooting.md` - Common issues and solutions

---

## 🔐 Security

Security is our top priority. We implement:

- 🔒 HTTPS everywhere
- 🔑 JWT-based authentication
- 📱 OTP phone verification
- 🛡️ AWS security groups and IAM roles
- 🔐 Encrypted data at rest and in transit
- 🚫 Private S3 buckets with CloudFront OAC
- 🔍 Regular security audits

**Found a security issue?** Please email security@cini.app (do not open a public issue)

---

## 📄 License

This project is proprietary and confidential. All rights reserved.

---

## 💬 Contact & Support

- 📧 **Email**: support@cini.app
- 🌐 **Website**: [www.cini.app](https://www.cini.app)
- 💼 **LinkedIn**: [Cini Labs](https://www.linkedin.com/company/cini-labs)
- 🐦 **Twitter**: [@CiniApp](https://twitter.com/CiniApp)

---

## 🙏 Acknowledgments

Built with ❤️ by the Cini Labs team

Special thanks to:
- The Ethiopian diaspora community for their feedback and support
- All contributors who help make Cini better
- Open source projects that power our platform

---

<div align="center">

**Made with 💝 for the Ethiopian diaspora community**

*Connecting hearts, preserving culture, building futures*

</div>

