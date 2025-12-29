# Go Email Dispatcher (Producer–Consumer)

A concurrent email dispatching service written in Go using
goroutines and channels. Emails are queued and processed
asynchronously by worker goroutines.

## Features
- Producer–consumer pattern using channels
- Configurable worker pool
- SMTP testing with Mailpit
- Graceful shutdown

## Tech Stack
- Go
- Mailpit (SMTP test server)

## How to Run
1. Start Mailpit
2. Run the Go service
3. Send test emails

<img width="956" height="417" alt="Screenshot 2025-12-30 043032" src="https://github.com/user-attachments/assets/378df8cd-05ce-4d78-b54f-15d7ad08808a" />
<img width="885" height="239" alt="Screenshot 2025-12-30 043101" src="https://github.com/user-attachments/assets/8a19d72b-ee97-4d50-b455-db251e92692b" />

## Learning Goals
- Go concurrency
- Channel-based communication
- Backend async processing

## Ongoing Project : Features To be Added
- User Segmentation
- Separate Campaigns
- Frontend
