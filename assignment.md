## Step 1

| Defect                        | Explanation                                 |
|-------------------------------|---------------------------------------------|
| No rentals in booking form | The drop-down menu in booking doesn't include any rentals |
| Date in booking form is missing functionality | Requirements state a check-in and checkout date. The current date input is only a single date selection |
| Guests in booking form has no cap | Requirements state a maximum of 12 guests. Currently, the system has no limit on number of guests |
| No cleaning fee | The booking form and bookings page do not mention the $50 cleaning fee |
| No confirmation on booking | There is nothing to indicate a successful booking on submit in the booking form |
| Search bar is nonfunctional | The search bar on the home page can be clicked on and has visible characters, but doesn't search for anything |
| Booking is allowed with missing / disallowed information | Booking form allows submission with no rental selected, an overage on guests, and an incomplete date |

## Step 2

| Field                            | Information |
| -------------------------------- | ----------- |
| Defect ID                        | #0001 |
| Title                            | Available Rentals Not Appearing In Drop Down |
| Date Reported                    | 11/19/2026 |
| Reporter                         | Evelyn Bushell |
| Application or Feature           | North Vacation Booking, AddBooking page |
| Test Environment                 | vscode |
| Preconditions                    | Install packages, load page |
| Steps to Reproduce               | Click on Add Booking, click drop-down menu on Rental |
| Expected Result                  | Drop-down menu offers available rentals |
| Actual Result                    | Drop-down menu is empty |
| Severity                         | Critical |
| Priority                         | High |
| Status                           | New |
| Related Requirement or Test Case | None |
| Supporting Evidence              | Rental maps through Formdata's rental array. The array is empty and doesn't import or fill from anything |

## Step 3

| Defect                   | Severity | Priority | Explanation                                   |
| ------------------------ | -------- | -------- | --------------------------------------------- |
| No rentals in booking form | Critical | High | This prevents customers from booking a rental
| Date in booking form is missing functionality | Critical | High | This prevents customers from booking a rental |
| Guests in booking form has no cap | High | High | A customer could book more guests than is safely manageable |
| No cleaning fee | High | High | Customers have no notice of this fee, possibly resulting in refunds or a lawsuite |
| No confirmation on booking | High | High | No visible confirmation could result in double booking and cancellations |
| Search bar is nonfunctional | Medium | Medium | Search bar currently has nothing to search for, but this needs confirmation once rentals are added |
| Booking is allowed with missing / disallowed information | Critical | High | Allows for invalid bookings and guaranteed cancellations and refunds |

