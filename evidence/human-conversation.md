# Evidence — Human Conversation

**Subject:** 2024 CSE grad, currently Platform Engineer, Hyderabad. Anonymous (ghost mode, no names). ~20 minutes, no personal data collected.

**Q: Most outdated R22 course on day 1?**
DevOps lab — college taught Jenkins freestyle jobs, `docker run`, Selenium IDE. First week required debugging a GitHub Actions YAML and an out-of-sync ArgoCD, having never opened a `.github/workflows` file. Same problem in CN labs: RIP protocol in Packet Tracer vs. real VPCs, load balancers, and Cloudflare-style edge in industry.

**Q: Day-1 skill the degree never taught?**
Git beyond commit/push — rebasing, resolving merge conflicts, PR reviews, writing a proper commit message. Force-pushed to main on day 1 and had it reverted by their lead. Also: reading logs/docs for hours (AWS docs, Kibana) — described as roughly 70% of the actual job.

**Q: Course more valuable in hindsight than it felt at the time?**
Operating Systems — disliked semaphores/paging/deadlocks in 3rd year, but now ties them directly to pods getting OOMKilled or CPU-throttled in Kubernetes. DBMS similarly reframed: joins/indexing/transactions matter directly when optimizing a slow query in production.

**Q: One credit-worth of content they'd add for 2030?**
"Shipping with GenAI + Cloud" — not ML theory, but practical RAG, vector DBs, prompt evaluation, cost control, and deploying via Terraform on cloud, including handling API keys and rate limits. Framed as directly job-readiness-defining for 2030.

**Q: Did theory-heavy courses (DAA, Compiler Design) help, or did tools make them redundant?**
Mixed: DAA called directly useful — time-complexity reasoning applies when debugging production timeouts. Compiler Design's hand-written LALR parser work called rarely used, but AST/optimization concepts still valuable — recommended teaching compilers through how tools like Babel/ESLint work, rather than only manual parse trees.

**Two findings pulled directly from this conversation:**
1. Computer Networks flipped KEEP→UPDATE (Section 3)
2. Git/version control confirmed as a double-sourced gap alongside JD3 (Section 5)
