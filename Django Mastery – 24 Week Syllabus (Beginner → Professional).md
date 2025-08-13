Perfect — here’s the **Django Mastery Weekly Syllabus** so you can follow it like a structured course.
It links **week → skills → resources → project tasks** so you never have to guess what to do next.

---

# **Django Mastery – 24 Week Syllabus (Beginner → Professional)**

## **Month 1 – Foundations**

**Goal:** Learn Django basics and build your first small apps.

| Week  | Skills                                                                                                | Resources                                                                                         | Project Tasks                                                                                                 |
| ----- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **1** | Python refresh, HTTP basics, MVT pattern, Django setup, project/app structure, URL routing, templates | [Django Official Tutorial – Part 1–2](https://docs.djangoproject.com/en/stable/intro/tutorial01/) | 1. Install Django & create project. 2. Make a simple "Hello Django" page. 3. Set up templates & static files. |
| **2** | Models, ORM basics, migrations, Django admin, static files                                            | [Django Official Tutorial – Part 3–4](https://docs.djangoproject.com/en/stable/intro/tutorial01/) | 1. Build **Personal Blog** with CRUD posts & categories. 2. Use Django admin for content.                     |
| **3** | Forms & ModelForms, validation, Bootstrap integration                                                 | [Django for Beginners – Forms Chapter](https://djangoforbeginners.com/)                           | 1. Create **To-Do List App** with add/edit/delete tasks. 2. Style with Bootstrap.                             |
| **4** | User authentication, login/logout, permissions, pagination                                            | [Django Auth Docs](https://docs.djangoproject.com/en/stable/topics/auth/)                         | 1. Add user accounts to Blog. 2. Add pagination for posts.                                                    |

---

## **Month 2 – Intermediate Core**

**Goal:** Work with files, custom queries, signals, and build APIs.

| Week  | Skills                                                       | Resources                                                                               | Project Tasks                                                            |
| ----- | ------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **5** | Advanced ORM queries (filter, annotate, select\_related)     | [Django ORM Cookbook](https://books.agiliq.com/projects/django-orm-cookbook/en/latest/) | 1. Add search & filtering to To-Do List. 2. Optimize queries.            |
| **6** | File/image uploads, media handling, custom user model basics | [Django File Upload Docs](https://docs.djangoproject.com/en/stable/topics/files/)       | 1. Create **Recipe Sharing Platform** with user profiles & images.       |
| **7** | Signals, slug fields, sitemaps, email sending                | [Django Signals Docs](https://docs.djangoproject.com/en/stable/topics/signals/)         | 1. Add email notifications to Recipe Platform when new recipe is posted. |
| **8** | Django REST Framework intro (serializers, viewsets, routers) | [DRF Quickstart](https://www.django-rest-framework.org/tutorial/quickstart/)            | 1. Create API endpoints for Recipe Platform. 2. Test with Postman.       |

---

## **Month 3 – Advanced Django**

**Goal:** Build secure APIs and introduce async tasks & caching.

| Week   | Skills                                                 | Resources                                                                                         | Project Tasks                                                    |
| ------ | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **9**  | Class-Based Views, mixins, custom DRF permissions      | [CBV Docs](https://docs.djangoproject.com/en/stable/topics/class-based-views/)                    | 1. Create **Blog API** with CBVs. 2. Add role-based permissions. |
| **10** | JWT auth with SimpleJWT, API versioning, rate limiting | [SimpleJWT Docs](https://django-rest-framework-simplejwt.readthedocs.io/)                         | 1. Secure Blog API with JWT.                                     |
| **11** | Celery + Redis for async tasks                         | [Celery with Django Docs](https://docs.celeryq.dev/en/stable/django/first-steps-with-django.html) | 1. Add async email sending to Blog API.                          |
| **12** | Caching (per-view, low-level, Redis caching)           | [Django Cache Docs](https://docs.djangoproject.com/en/stable/topics/cache/)                       | 1. Add caching to Recipe API for faster response.                |

---

## **Month 4 – Real-Time & Testing**

**Goal:** Add WebSockets, notifications, and automated tests.

| Week   | Skills                                               | Resources                                                                | Project Tasks                                                   |
| ------ | ---------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------- |
| **13** | Django Channels basics, WebSockets, consumers        | [Django Channels Docs](https://channels.readthedocs.io/)                 | 1. Create **Chat App** with real-time messaging.                |
| **14** | Private/group chats, chat history, typing indicators | Channels Groups section                                                  | 1. Extend Chat App with group chats & history.                  |
| **15** | Signals + Channels for notifications                 | [Signals Docs](https://docs.djangoproject.com/en/stable/topics/signals/) | 1. Add notifications for new messages.                          |
| **16** | Testing (pytest + Django TestCase), CI basics        | [pytest-django Docs](https://pytest-django.readthedocs.io/)              | 1. Add unit tests to Chat App. 2. Set up GitHub Actions for CI. |

---

## **Month 5 – Full-Stack & Deployment**

**Goal:** Build API-driven systems, integrate frontend, and deploy.

| Week   | Skills                                     | Resources                                                                                                                 | Project Tasks                                    |
| ------ | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **17** | CORS handling, API docs (Swagger/drf-yasg) | [drf-yasg Docs](https://drf-yasg.readthedocs.io/en/stable/)                                                               | 1. Create **Booking API** with docs.             |
| **18** | React/Next.js basics, API integration      | [React + Django Guide](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react) | 1. Build Booking App frontend in React/Next.js.  |
| **19** | Dockerizing Django + Postgres + Redis      | [Docker Django Guide](https://docs.docker.com/samples/django/)                                                            | 1. Containerize Booking App with docker-compose. |
| **20** | Deployment with Nginx + Gunicorn, HTTPS    | [DigitalOcean Django Deployment](https://www.digitalocean.com/community/tutorials/how-to-deploy-django-to-production)     | 1. Deploy Booking App to VPS.                    |

---

## **Month 6 – Scaling & Pro-Level**

**Goal:** Build a production-ready SaaS with advanced features.

| Week   | Skills                                             | Resources                                                                              | Project Tasks                                           |
| ------ | -------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| **21** | Multi-tenant architecture, PostgreSQL optimization | [High Performance Django PDF](https://highperformancedjango.com/)                      | 1. Start **SaaS Platform** backend with tenant support. |
| **22** | Role-based access control, advanced permissions    | DRF Permissions Docs                                                                   | 1. Add RBAC to SaaS Platform.                           |
| **23** | Logging (Sentry), monitoring (Prometheus, Grafana) | [Sentry Docs](https://docs.sentry.io/platforms/python/guides/django/)                  | 1. Add monitoring to SaaS Platform.                     |
| **24** | Security hardening, scaling with Docker swarm/K8s  | [Django Security Checklist](https://docs.djangoproject.com/en/stable/topics/security/) | 1. Finalize SaaS Platform and run security audit.       |

---

✅ **How to Use This Syllabus:**

* **Commit daily** to GitHub — even small progress matters.
* **Follow weeks strictly** — don’t jump ahead until current week’s project is working.
* Every month, **refactor old projects** using new skills.
* Keep a **portfolio repo** where you showcase final versions.

---

