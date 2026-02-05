# Bharat Sahayak – System Design Document

## Architecture Overview
Bharat Sahayak follows a serverless, cloud-native architecture using AWS managed services to ensure scalability, low cost, and ease of maintenance.

## System Components

### User Interface
- Mobile/Web Application
- Voice and text input support
- Low-bandwidth friendly UI

### AI & Language Processing
- Amazon Transcribe for Speech-to-Text
- Amazon Translate for multilingual support
- Amazon Bedrock (LLM) for AI understanding and response generation
- Retrieval Augmented Generation (RAG) for accurate scheme information

### Backend Services
- AWS Lambda for business logic and eligibility checks
- Amazon API Gateway for secure API communication

### Data Storage
- Amazon DynamoDB for scheme and eligibility data
- Amazon S3 for documents, FAQs, and reference material

### Response Layer
- Amazon Polly for Text-to-Speech voice responses

## Security & Monitoring
- AWS IAM for access control
- Amazon CloudWatch for logging and monitoring

## Design Highlights
- Voice-first and inclusive
- Fully serverless and scalable
- Cost-efficient pay-as-you-go model
- Optimized for Bharat-scale usage
