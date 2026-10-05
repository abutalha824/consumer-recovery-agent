 # Consumer Recovery Agent

> Turn a consumer problem into a structured recovery case.

Consumer Recovery Agent is an MVP prototype designed to help consumers organize refund, cancellation, payment, product, subscription, and service-related recovery cases.

The application turns an unstructured consumer complaint into a structured case with classification, priority, evidence requirements, recovery guidance, and a prepared merchant communication.

## 🚀 Live Demo

[Open Consumer Recovery Agent](https://consumer-recovery-agent-hg3x.vercel.app/)

## 💡 What Problem Does It Solve?

Consumers often have a problem but do not know:

- What evidence they need
- How serious their case is
- What action to take next
- How to explain the issue clearly to a merchant
- Whether their recovery case is ready to move forward

Consumer Recovery Agent organizes this process into a simple workflow.

## ✨ Key Features

### 1. Recovery Case Creation

Users can create a case by entering:

- Merchant / Company
- Amount involved
- What happened
- What they want recovered
- Supporting evidence

### 2. Case Classification

The prototype automatically classifies cases into categories such as:

- Refund Recovery
- Subscription Issue
- Cancellation Dispute
- Product Dispute
- Payment / Service Dispute
- Other

### 3. Priority Detection

Cases are assigned a priority level based on the information provided.

Example:

**High Priority**

### 4. Evidence Tracking

Each case has an evidence checklist.

Example evidence requirements:

- Payment / transaction proof
- Order or purchase proof
- Return or refund confirmation
- Previous communication with the merchant

Users can upload evidence against individual checklist items and track completion.

Example:

**Evidence readiness: 4 of 4 complete (100%)**

### 5. Recovery Action

The system recommends the next recovery action based on the case type.

For example:

**Verify the refund status**

The user is then guided toward reviewing the relevant evidence and preparing a merchant resolution request.

### 6. Recovery Message

The application generates a structured recovery message that the user can copy and send to the merchant.

The prototype does not automatically send messages to merchants.

### 7. Case Activity Timeline

Each case keeps track of important actions such as:

- Case created
- Case analyzed
- Evidence checklist generated
- Evidence uploaded
- Recovery action prepared

### 8. Local Case Storage

Cases are stored locally in the user's browser so the prototype can maintain case information during testing.

## 🧭 Example Workflow

Consumer Problem → Create Recovery Case → Analyze Case → Classify Problem → Identify Priority → Generate Evidence Checklist → Upload / Track Evidence → Evidence Ready → Prepare Recovery Action → Generate Merchant Message

## 🧪 Example Case

**Merchant:** Amazon

**Amount:** ₹1,999

**Case Type:** Refund Recovery

**Priority:** High

**Recovery Goal:** I want my ₹1,999 refund.

**Evidence:** 4 / 4 complete

**Recommended Action:** Verify the refund status and prepare a merchant resolution request.

## 🛠️ Technology

This MVP currently uses:

- HTML
- CSS
- JavaScript
- Browser Local Storage
- GitHub
- Vercel

The current version is intentionally lightweight and runs as a front-end prototype.

## 📁 Project Structure

The project contains two main files:

- index.html — main application
- README.md — project documentation

## 🎯 Current MVP Capabilities

The current prototype can:

- Create consumer recovery cases
- Classify consumer problems
- Assign priority
- Generate evidence requirements
- Track evidence completion
- Track uploaded evidence filenames locally
- Recommend a recovery action
- Generate a recovery message
- Copy the recovery message
- Maintain a case activity timeline
- Store cases locally in the browser

## ⚠️ Current Limitations

This project is currently an MVP prototype.

It does not currently connect to:

- Real merchant systems
- Payment providers
- Legal services
- Government consumer complaint systems
- External recovery APIs
- Email or messaging services

Evidence files are currently tracked locally in the browser by filename and metadata. They are not uploaded to an external storage service.

Case classification and recommendations are currently rule-based rather than powered by a production AI model.

## 🔮 Future Development

Possible future improvements include:

- AI-powered case classification
- Secure cloud database
- Real file storage
- User authentication
- Merchant integrations
- Payment-provider integrations
- Email integration
- WhatsApp / messaging integration
- Consumer complaint platform integrations
- Automated follow-ups
- Case status notifications
- Analytics dashboard
- Multi-user accounts
- Secure evidence storage
- Advanced recovery recommendations

## 📌 Project Status

**MVP Prototype — Active Development**

The current version focuses on validating the consumer recovery workflow and user experience before adding external integrations and production infrastructure.

## 👨‍💻 Project

Built as a practical prototype exploring how an AI-assisted workflow can help consumers organize and pursue recovery cases.

---

**Live Demo:**  
https://consumer-recovery-agent-hg3x.vercel.app/

**Repository:**  
https://github.com/abutalha824/consumer-recovery-agent
