# Phase 6 – Project Testing

## Test Scope
End-to-end testing of all three planners with real-world budgets, plus authentication and history.

## Test Cases
| ID | Module | Input | Expected Result | Status |
|----|--------|-------|-----------------|--------|
| TC01 | Register | New username/password | Account created | Pass |
| TC02 | Login | Valid credentials | JWT issued, dashboard opens | Pass |
| TC03 | Login | Wrong password | Error message shown | Pass |
| TC04 | Home Planner | Budget + living room, 3 lights, 2 fans | Item list within budget (IKEA/Amazon) | Pass |
| TC05 | Party Planner | Budget, guests, birthday | Catering/decor/entertainment split | Pass |
| TC06 | Jewelry Planner | Budget, occasion, outfit image | Matching jewelry suggestions | Pass |
| TC07 | Any planner | Empty / invalid budget | Validation error | Pass |
| TC08 | AI failure | Insufficient AI response | Fallback recommendations shown | Pass |
| TC09 | History | Open `/history` | Past queries listed | Pass |
| TC10 | Logout | Click logout | Session ended, redirect to login | Pass |

> Update the Status column with your actual results before submission.

## Optimization Done
Prompt refinement, input validation, fallback recommendations, session handling, responsive UI.
