# Investigation Task

You have been assigned to investigate a production issue affecting the api-gateway service in the `production` namespace.

Users are unable to access the service.

---

## Your Task

Investigate the Kubernetes environment and identify the root cause(s) of the outage.

You must:
- Inspect all relevant Kubernetes resources
- Identify every issue affecting service availability
- Fix the issues without deleting and recreating the deployment

---

## Constraints

- Do NOT delete and recreate resources
- Do NOT assume a single root cause — there may be multiple issues
- Explain what you observe before applying each fix

---

## Expected Outcome

By the end of your investigation:
- All pods must be in `Running` and `Ready` state
- The service must have healthy endpoints
- The application must be reachable inside the cluster