# Bajaj_Java_Backend
# 💡 Follower Graph App – Bajaj Finserv Health Challenge (SRM April 2025)

This Spring Boot application was developed for the **Bajaj Finserv Health Programming Challenge**.  
It automatically interacts with a remote API, solves a graph-based user follow problem based on the `regNo`, and submits the result to a secured webhook with JWT authentication.

---

## 🚀 Features

✅ Auto-start on app launch  
✅ Calls `/generateWebhook` API  
✅ Dynamically solves:
- **Question 1** – Mutual Followers *(if regNo ends in odd digits)*
- **Question 2** – Nth-Level Followers *(if regNo ends in even digits)*  
✅ JWT Authorization  
✅ Retry webhook POST up to 4 times on failure

---
