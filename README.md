# Quiz-Master (Built using SpringBoot - React, with PostreSQL DB) ( https://quiz-ui-three.vercel.app/ )

• Quiz-Master is a quiz platform for users to practice, review and download results and contribute to a pool of 1000+ questions.

• Users can customize quiz as per their need with support for 5+ topics, 3 difficulty levels, number of questions, and time limitations.

• User authentitcation is done using JWT access token and a refresh token, passwords stored with encryption using Bcrypt.

• Webhooks are configured to trigger auto build and deployment of changes after any push to main branch.

• Deployed the SpringBoot service on Render and connected to PostgreSQL on Neon in same region to reduce latency.

• Optimized data access with in-memory caching with Caffeine and indexing, leading to 70% fewer DB queries and 200ms faster APIs.

• Actuator endpoints have been set-up to monitor the service and heartbeat mechanism configured using cron-job with downtime alert, to ensure 24*7 availability.
