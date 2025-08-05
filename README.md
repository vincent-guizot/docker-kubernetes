# 🚀 Docker + Kubernetes Roadmap (for 5+ YOE Full Stack Dev)

This is a fast-track hands-on roadmap to master Docker and Kubernetes with curated links and exercises.

---

## 🔹 PHASE 1: Docker (1–2 Days)

### ✅ Learn the Fundamentals
- [Docker Official Docs – Get Started](https://docs.docker.com/get-started/)
- [Docker Curriculum – Practical Guide](https://docker-curriculum.com/)
- [Play with Docker – Online Playground](https://labs.play-with-docker.com/)

### 🛠️ Exercises
- [ ] Build a simple Node.js or Go app → Containerize it
- [ ] Add a second container (e.g., Postgres) using `docker-compose.yml`
- [ ] Tag and push your image to [Docker Hub](https://hub.docker.com/)
- [ ] Try volume + bind mount
- [ ] Try multi-stage builds in Dockerfile

---

## 🔹 PHASE 2: Kubernetes (3–4 Days)

### ✅ Learn the Core Concepts
- [Kubernetes Official Docs – Concepts](https://kubernetes.io/docs/concepts/)
- [Kubernetes in Simple Words – YouTube](https://www.youtube.com/watch?v=X48VuDVv0do) (TechWorld with Nana)
- [Learn Kubernetes by Doing – Katacoda](https://www.katacoda.com/courses/kubernetes)
- [Kubernetes by Example](https://kubernetesbyexample.com/)

### 🛠️ Exercises
- [ ] Set up local cluster with [minikube](https://minikube.sigs.k8s.io/docs/)
- [ ] Deploy your container as a `Deployment`
- [ ] Expose with `Service` (ClusterIP, NodePort, LoadBalancer)
- [ ] Add `ConfigMap` and `Secrets`
- [ ] Scale app with `kubectl scale`
- [ ] Try rolling updates

---

## 🔹 PHASE 3: Real-World Project (2–3 Days)

### 🧠 Use Case Project
- Build & deploy a **3-tier app** (API + Redis + DB)
- Create all K8s YAMLs:
  - `deployment.yaml`
  - `service.yaml`
  - `ingress.yaml`
  - `configmap.yaml`
  - `secret.yaml`
- Host locally using `minikube` or try [Play with Kubernetes](https://labs.play-with-k8s.com/)

### 🧪 Real Exercises
- [ ] Simulate pod failure and auto-recovery
- [ ] Use `liveness` and `readiness` probes
- [ ] Add a `HorizontalPodAutoscaler`
- [ ] Internal DNS and service discovery between containers

---

## 🔹 BONUS: Cloud & CI/CD

- [Google Cloud Kubernetes Engine – Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart)
- [CI/CD with GitHub Actions and Kubernetes](https://docs.github.com/en/actions/deployment/deploying-to-your-cloud-provider/deploying-to-kubernetes)

---

## ✅ Summary Checklist

| Task                                  | Done |
|---------------------------------------|------|
| Docker container + compose setup      | [ ]  |
| Push to DockerHub                     | [ ]  |
| Minikube deployment + service         | [ ]  |
| YAML files for deployment             | [ ]  |
| ConfigMap and Secrets                 | [ ]  |
| Liveness/readiness probes             | [ ]  |
| Autoscaler                            | [ ]  |
| 3-tier app deployed in K8s            | [ ]  |
| CI/CD pipeline with GitHub Actions    | [ ]  |

---

_💡 Tip: Document your journey on GitHub with each exercise/project to build your DevOps portfolio._



