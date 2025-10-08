# Jenkins CI/CD Pipeline
this projects features a complete, well structured and optimized jenkins pipeline used to deploy a node.js app to netlify.com 
The pipeline is designed for efficiency, running build and test stages with parallel execution for unit and end-to-end (E2E) tests.

Key highlights:

- Parallel Testing: Unit tests (via Jest) and E2E tests (via Playwright) run concurrently to minimize pipeline duration.
- Containerized Environments: Uses Docker images for consistency across builds and tests (Node.js for build/unit, Playwright for E2E).
- Artifact Publishing: Automatically generates and publishes test reports (JUnit for unit tests, HTML for Playwright E2E).

  <img width="675" height="191" alt="Screenshot from 2025-10-08 08-53-00" src="https://github.com/user-attachments/assets/f4866e62-859b-4ef1-985e-a680283c2143" />
