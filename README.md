# Landing Page Lead Funnel Validation Tool

## Overview
The goal of this take home assignment is to create a web app that helps companies validate their "Book a Demo" conversion flow. The application should take a URL and verify that new users can successfully schedule a demo meeting through the company's landing page.

## Core Requirements
1. Create a web app with a simple interface where users can:
   - Input a company's landing page URL
   - Trigger automated testing of the demo booking flow
   - View test results and insights

2. The application should test the demo booking functionality:
   - Detect "Book a Demo" (or similar) buttons/links
   - Click through to the booking flow
   - Fill out any required forms
   - Complete the meeting scheduling process
   - Verify the booking was successful (e.g., confirmation page)

3. Present test results in a clear, user-friendly format showing:
   - Whether the demo booking flow was found
   - If the booking process completed successfully
   - Any errors or issues encountered

## Stretch Goals (Optional)
- Capture metrics from the browser (e.g. console logs, network information, etc.)
- Support alternative lead capture mechanisms:
  - Contact forms (e.g., "Contact Sales" flows)
- Include retry mechanisms for flaky tests

## Technical Guidelines
- You may use any programming languages, frameworks, or tools you prefer

## Examples
- https://www.revyl.ai./ - validate "book a demo" button is clickable and leads to a booking page, books a meeting and then validates the booking was successful.

---
Note: This is an open-ended assignment designed to evaluate your problem-solving approach. Focus on delivering a working solution that demonstrates your ability to ship fast.