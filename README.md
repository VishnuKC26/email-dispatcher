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

## Learning Goals
- Go concurrency
- Channel-based communication
- Backend async processing

## Ongoing Project : Features To be Added
- User Segmentation
- Separate Campaigns
- Frontend
