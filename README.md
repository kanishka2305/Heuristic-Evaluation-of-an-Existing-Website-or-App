# Unit-3 Heuristic-Evaluation-of-an-Existing-Website-or-App
## AIM
To perform heuristic evaluation on two competing apps/websites, propose design improvements, and evaluate the impact of the improvements using A/B testing.

## PROBLEM STATEMENT
Many apps/websites suffer from poor user experience (UX) due to design flaws. This experiment aims to compare two competing platforms, identify usability issues through heuristic evaluation, suggest improvements, and assess the impact of changes using A/B testing.

## DESIGN STEPS
### Select Competing Apps/Websites:
App A: Zomato App B: Swiggy

### Conduct Heuristic Evaluation
Evaluate both apps using Nielsen’s 10 Usability Heuristics: Visibility of system status Match between system and real world User control and freedom Consistency and standards Error prevention Recognition rather than recall Flexibility and efficiency of use Aesthetic and minimalist design Help users recognize, diagnose, and recover from errors Help and documentation

### Identify Usability Issues:
Zomato: Overcrowded interface, poor error messaging Swiggy: Inconsistent button labels, missing confirmation on cancellation

### Propose Design Changes:
Zomato: Simplify layout, add tooltips for error messages Swiggy: Unify button labels, add cancellation confirmation dialog

### Design A/B Testing:
A Version: Original design B Version: Modified design

Users split into two groups (randomly assigned) Metrics: Task completion time, error rate, satisfaction score (via post-task survey)

### Conduct User Testing:
10 users for each version Tasks: Search food item, place order, cancel order

## DESIGNS
### Zomato - Original (A):
Home screen with multiple banners, mixed fonts No tooltip or explanation when order fails

![image](https://github.com/user-attachments/assets/791a80ae-3af5-4768-ad0b-3a9607241cde)

When order fails:

## Zomato - Modified (B):
Minimal layout with clear sections Error tooltip on order failure explaining

![image](https://github.com/user-attachments/assets/e8929400-393f-4961-ad12-a4fad25e0c13)
issue

## Swiggy - Original (A):
"Go Back", "Return", and "Cancel" buttons used interchangeably 

![image](https://github.com/user-attachments/assets/94311d21-aa9f-4b95-8734-2552c129730f)
cancellation happens instantly

## Swiggy - Modified (B):
All buttons renamed to "Cancel Order" or "Go Back" appropriately Confirmation dialog before cancellation

![image](https://github.com/user-attachments/assets/28dbd514-6a0f-44f3-9411-926c3c3d5b29)

## RESULTS
App Version Task Completion Time (avg)** Errors User Satisfaction (1–5) Zomato A 2.4 min 5 3.2 Zomato B 1.8 min 1 4.4 Swiggy A 2.1 min 4 3.5 Swiggy B 1.7 min 0 4.6

## Conclusion
The heuristic evaluation helped identify several UX issues in Zomato and Swiggy. After implementing suggested design improvements, A/B testing showed clear gains in task efficiency, reduced errors, and increased user satisfaction. This validates the effectiveness of UX redesign guided by heuristic principles.
