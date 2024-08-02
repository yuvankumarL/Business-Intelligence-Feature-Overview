# Business-Intelligence-Feature-Overview









QA Intern – Assessment

NapQueen

QA (Business Intelligence Feature Overview)

Submitted by

Yuvankumar L
(20MIS0395)
















# TEST CASE REPORT

## SOV Dashboard / Brand Analytics - Keyword Filter:
Test Case ID: TC001
Title: Verify Keyword Filter Functionality on SOV Dashboard
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the Business Intelligence Dashboard.
    2. Select a keyword from the "Keyword" filter dropdown (e.g., "zinus mattress").
    3. Ensure that options are selected in all other filters (Range, Position, Frequency, Brand).
    4. Click the "Run" button.
    5. Verify that the data updated to show products related to the selected keyword.
    6. Repeat steps 2-5 with different keywords to cover the possible scenarios.
Expected Result:
    • The data should update to display only products related to the selected keyword.
Actual Result:
    • The data updated correctly, showing only products related to the keywod mentioned.
Status: Pass

## SOV Dashboard / Brand Analytics - Range Filter:
Test Case ID: TC002
Title: Verify Range Filter Functionality on SOV Dashboard
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Select a range from the "Range" filter dropdown (e.g., "Last 7 Days").
    3. Ensure that options are selected in all other filters (Keyword, Position, Frequency, Brand).
    4. Click the "Run" button.
    5. Verify that the data updated to show products related to the selected Range.
    6. Repeat steps 2-5 with different Range to cover the possible scenarios.
Expected Result:
    • The data should update to reflect the selected time range.
Actual Result:
    • The data updated correctly, showing only products releated to the specific dates except the “Custom Range” option. The selection date is not working properly.
Status: Fail

## SOV Dashboard / Brand Analytics - Position Filter:
Test Case ID: TC003
Title: Verify Position Filter Functionality on SOV Dashboard
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Select a position from the "Position" filter dropdown (e.g., "All").
    3. Ensure that options are selected in all other filters (Keyword, Range, Frequency, Brand).
    4. Click the "Run" button.
    5. Verify that the data updated to show products related to the selected Position.
    6. Repeat steps 2-5 with different Position to cover the possible scenarios.
Expected Result:
    • The data should update to reflect the selected position.
Actual Result:
    • The data updated correctly, showing only products releated to the specific position selected.
Status: Pass

## SOV Dashboard / Brand Analytics - Frequency Filter:
Test Case ID: TC004
Title: Verify Frequency Filter Functionality on SOV Dashboard
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Select a frequency from the "Frequency" filter dropdown (e.g., "Daily").
    3. Ensure that options are selected in all other filters (Keyword, Range, Position, Brand).
    4. Click the "Run" button.
    5. Verify that the data updated to show products related to the selected Frequency.
    6. Repeat steps 2-5 with different Frequency to cover the possible scenarios.
Expected Result:
    • The data should update to reflect the selected frequency.
Actual Result:
    • The data updated correctly, showing only products releated to the specific frequency selected.
Status: Pass


## SOV Dashboard / Brand Analytics – Pagination:
Test Case ID: TC005
Title: Verify the pages displayed as per the rows selected
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Ensure that all options are selected in all the filters (Keyword, Range, Position, Brand).
    3. Click the "Run" button.
    4. Verify that the data updated to show products related to the selected Frequency.
    5. Navigate to All Brand Coverage Section.
    6. Select the number of rows required in the page (eg., “10”).
    7. Verify that the page contains the rows as selected
    8. Repeat steps 6-7 with different number of rows to cover the possible scenarios.
Expected Result:
    • The Pages should display the rows as selected.
Actual Result:
    • The Pages updated correctly, showing only the number of rows as selected.
Status: Pass

## SOV Dashboard / Brand Analytics – Pagination:
Test Case ID: TC006
Title: Verify the Navigation of Pages.
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Ensure that all options are selected in all the filters (Keyword, Range, Position, Brand).
    3. Click the "Run" button.
    4. Verify that the data updated to show products related to the selected Frequency.
    5. Navigate to All Brand Coverage Section.
    6. Select the number of rows required in the page (eg., “10”).
    7. Verify that the page contains the rows as selected
    8. Click the navigation buttons.
    9. Verify whether the pages moves as per the buttons selected.
    10. Navigate to the goto textfield.
    11. Enter the page number you want to view.
    12. Verify whether it navigates to the page number you entered.
Expected Result:
    • The Pages should display the rows as selected 
    • Navigates to the page number entered.

Actual Result:
    • The Pages updated correctly, showing only the number of rows as selected. 
    • Navigated to the page number entered but it also navigates to the page number the exceeds the maximum number of pages at present.
Status: Pass  Fail

## Keyword Tracker - Add Keyword:
Test Case ID: TC007
Title:  Verify adding a new keyword to the tracker
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the Keyword Tracker Page.
    2. Click Add New Keyword.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Enter the keyword need to be added in the textfield.
    5. Click Enter.
    6. Click Track Keywords.
    7. Popup Status.
    8. Verify that the keyword appears in the list of tracked keywords.
Expected Result:
    • Keyword Addition Successful.
Actual Result:
    • Keyword Addition Successful.
    • But the keyword added and updated timing is incorrect.
Status: Partially Pass

## Keyword Tracker - Add Keywords:
Test Case ID: TC008
Title:  Verify adding a bulk of new keyword to the tracker
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the Keyword Tracker Page.
    2. Click Add New Keyword.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Click or drag to upload file
    5. After file uploaded.
    6. Click Track Keywords.
    7. Popup Status.
    8. Verify that the keyword appears in the list of tracked keywords.
Expected Result:
    • Keyword Addition Successful.
Actual Result:
    • Keyword Limit Reached on Walmart
    • Keyword limit has been reached on Walmart. Please remove some keywords and try again.
Status: Fail

## Keyword Tracker – Change Status:
Test Case ID: TC009
Title:  Verify the status of keyword.
Precondition: Access to the Business Intelligence feature.
Steps:
    1 Navigate to the Keyword Tracker Page.
    2 Select Marketplace (eg., “Amazon” or “Walmart”).
    3 Activate the Inactive Keyword.
        3.1 Navigate to the Inactive keywords.
        3.2 Select the keyword whose status need to be activated.
        3.3 Turn on the check box.
        3.4 Click change.
        3.5 Pop “Keyword updation Successful”.
        3.6 Verify that the keyword appears in the list of Active keywords.
    4 Inactivate the active keyword.
        4.1 Navigate to the Active keywords.
        4.2 Select the keyword whose status need to be inactivated.
        4.3 Turn off the check box.
        4.4 Click change.
        4.5 Pop “Keyword updation Successful”.
        4.6 Verify that the keyword appears in the list of inactive keywords.
       
Expected Result:
    • The keyword status is changed to inactive.
Actual Result:
    • The keyword status is changed to inactive.
Status: Pass

## Keyword Tracker - Delete Keyword:
Test Case ID: TC010
Title:  Verify deleting keyword from the tracker.
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the Keyword Tracker Page.
    2. Navigate to the active or inactive keywords.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Select the keyword.
    5. Click Delete Icon.
    6. Click Delete.
    7. Popup Status.
    8. Verify that the keyword disappears in the list of tracked keywords.
Expected Result:
    • Keyword Deletion Successful.
Actual Result:
    • Keyword Deletion Successful.
Status: Pass

## UI Stability Testing – Reszie the browser:
Test Case ID: TC011
Title:  Verify Whether the website working with different sizes.
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Open the Business Intelligence feature in a maximized browser window.
    2. Slowly resize the browser window horizontally from maximum width to minimum width.
    3. Observe the UI elements during resizing.
    4. Resize the browser window back to maximum width.
    5. Repeat steps 3-5, but resize vertically this time.
Expected Result:
    • During resizing, UI elements should adjust smoothly without flickering or jumping.
    • No UI elements should disappear unexpectedly during resizing.
Actual Result:
    • Currently this website is not compatible in mobile view.
Status: Fail

## UI Stability Testing – Navigate to different website pages:
Test Case ID: TC012
Title:  Verify Whether the website navigating with differnt pages.
Precondition: Access to the Business Intelligence feature.

Steps:
    1. Navigate to the SOV Dashboard page.
    2. Navigate to the Keyword Tracker page.
    3. Click ‘<-’ or ‘Alt+<-’ to move backward to the SOV Dashboard page. 
    4. Verify whether the pages navigate correctly.
Expected Result:
    • The page should navigate to SOV Dashboard Page.
Actual Result:
    • The page is still on the current page.
Status: Fail

## UX Quality – Data Visualization:
Test Case ID: TC013
Title:  Verify the charts.
Precondition: Access to the Business Intelligence feature.
Steps:
    1. Navigate to the SOV Dashboard page.
    2. Ensure that options are selected in all filters (Keyword, Range, Position, Frequency, Brand).
    3. Click the "Run" button.
    4. Verify that the data updated to show products related to the selected Range.
    5. Navigate to the chart section.
    6. Verify the color pattern.
    7. Navigate to the All brand coverage section.
    8. Selct the brand and click “View trend”.
    9. Verify the charts changes according to the brand choosen.
    10. Verify the chart when navigating to the colors the details of the brand is shown.
    11. Click the brand (eg., NapQueen, etc..).
    12. Navigate to the all products under the brand.
    13. Verify the product link is working.
Expected Result:
    • The color pattern should be user friendly.
    • The trend of the selected product should reflect in the chart.
    • While moving around the colors in the chart, the data’s of the brands should display according to the color.
    • The products of the brand should be displayed.
    • The chart of different products.
    • The product link should navigate to the purchase link.
Actual Result:
    • The color pattern is user friendly.
    • The trend of the selected product reflected in the chart.
    • While moving around the colors in the chart, the data’s of the brands displayed according to the color.
    • The products of the brand is displayed.
    • The chart of different products.
    • The product link navigated to the purchase link.
Status: Pass

## Cross-Browser Testing – Reszie the browser:
Test Case ID: TC014
Title:  Verify the website working in different browsers.
Precondition: Access to the Business Intelligence feature.
Steps:
    1 Open the Chrome Browser
        1.1 Version: 127.0.6533.89
        1.2 Open the Business Intelligence feature in a maximized browser window.
        1.3 Verify whether the website works correctly.
    2 Open the Microsoft Edge
        2.1 Version: 127.0.2651.74
        2.2 Open the Business Intelligence feature in a maximized browser window.
        2.3 Verify whether the website works correctly.
    3 Open the Firefox Browser
        3.1 Version: 128.0.3
        3.2 Open the Business Intelligence feature in a maximized browser window.
        3.3 Verify whether the website works correctly.
Expected Result:
    • During resizing, UI elements should adjust smoothly without flickering or jumping.
    • No UI elements should disappear unexpectedly during resizing.
Actual Result:
    • Currently this website is not compatible in mobile view.
Status: Pass







# BUG REPORT

## Title: SOV Dashboard / Brand Analytics – Custom Range Filter
Bug ID: B001
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When selecting date on calendar from “Custom Range” from Range filter, after selecting month and year, it is not navigating to that month page to select date.
Steps to Reproduce:
    1. Navigate to the SOV Dashboard page.
    2. Select “Custom Range” from the "Range" filter.
    3. Click the calendar icon from “from date”
    4. Select the button with month and year.
    5. Select Month and year.
    6. Select the from date from the current month.
    7. Repeat step 3-6 for the “to date”.
    8. Ensure that options are selected in all other filters (Keyword, Position, Frequency, Brand).
    9. Click the "Run" button.
    10. Verify that the data updated to show products related to the selected Range.
Expected Result: The data should update to reflect the selected filter options.
Actual Result: The date is not accesible from the calendar after selecting month and year.
Severity: Low
Priority: Low
Screenhot:
	
Additional Information: This issue affects the functionality of the filters from selecting date.

## Title:SOV Dashboard / Brand Analytics, Keyword Tracker – Goto in Pagination:
Bug ID: B002
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When entering the page number that exceeds the maximum page limit still it navigates to that page number. (eg., when the maximum page limit is 22, when i enter 100 in the goto section it navigates to the 100th page).
Steps to Reproduce:
    1 Navigate to the SOV Dashboard page.
        1.1 Ensure that all options are selected in all the filters (Keyword, Range, Position, Brand).
        1.2 Click the "Run" button.
        1.3 Verify that the data updated to show products related to the selected Frequency.
        1.4 Navigate to All Brand Coverage Section.
        1.5 Select the number of rows required in the page (eg., “20”).
        1.6 Verify that the page contains the rows as selected
        1.7 Navigate to the goto textfield.
        1.8 Enter the page number you want to view. (eg., “100”)
        1.9 Verify whether it navigates to the page number you entered.
    2 Navigate to the Keyword Tracker page.
        2.1 Select the number of rows required in the page (eg., “20”).
        2.2 Verify that the page contains the rows as selected
        2.3 Navigate to the goto textfield.
        2.4 Enter the page number you want to view. (eg., “100”)
        2.5 Verify whether it navigates to the page number you entered.
Expected Result: The goto textfield should not accept the page number greater than the maximum page limits.
Actual Result: The page is navigated to the page number that exceeds the maximum page limit.
Severity: Medium
Priority: High
Screenshot:
	
Additional Information: This issue affects the functionality of the page.

## Title:Keyword Tracker - Add Keyword Timing
Bug ID: B003
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Time: 10:37 pm (India GMT+5:30) 
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When adding new keyword the added and updated time of the keyword is wrong.
Steps to Reproduce:
    1. Navigate to the Keyword Tracker Page.
    2. Click Add New Keyword.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Enter the keyword need to be added in the textfield.
    5. Click Enter.
    6. Click Track Keywords.
    7. Popup Status.
    8. Verify that the keyword appears in the list of tracked keywords.
    9. Verify the time of added and updated time of new keyword.

Expected Result: The product added and updated time should contain the time 10:37 pm.
Actual Result: The product added and updated time is 10:05 am.
Severity: Medium
Priority: High
Screenshot:
	
Additional Information: This issue affects the functionality of the keyword added and updated timings.

## Title:Keyword Tracker – Add Bulk Keywords
Bug ID: B004
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Time: 10:37 pm (India GMT+5:30) 
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When adding bulk of new keywords to the keywords section it is not accepting.
Steps to Reproduce:
    1. Navigate to the Keyword Tracker Page.
    2. Click Add New Keyword.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Click or drag to upload file
    5. After uploading file that contains more than 20 items.
    6. Click Track Keywords.
    7. Popup Status.
    8. Verify that the keyword appears in the list of tracked keywords.
Expected Result:
    • Keyword Addition Successful.
Actual Result:
    • Keyword Limit Reached on Walmart
    • Keyword limit has been reached on Walmart. Please remove some keywords and try again.
Severity: Medium
Priority: High
Screenshot:

	
Additional Information: This issue affects the functionality of adding keywords.

## Title:Keyword Tracker – Add Bulk Keywords in Amazon
Bug ID: B005
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Time: 10:37 pm (India GMT+5:30) 
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When adding a bulk of new keywords to the amzon marketplace the error message contains the name (“Walmart” instead of “Amazon”).
Steps to Reproduce:
    1. Navigate to the Keyword Tracker Page.
    2. Click Add New Keyword.
    3. Select Marketplace (eg., “Amazon” or “Walmart”).
    4. Click or drag to upload file
    5. After uploading file that contains more than 20 items.
    6. Click Track Keywords.
    7. Popup Status.
    8. Verify that the keyword appears in the list of tracked keywords.
Expected Result:
    • Keyword Limit Reached on Amazon.
    • Keyword limit has been reached on Amazon. Please remove some keywords and try again.
Actual Result:
    • Keyword Limit Reached on Walmart
    • Keyword limit has been reached on Walmart. Please remove some keywords and try again.
Severity: Medium
Priority: High
Screenshot:

	
Additional Information: This issue affects the functionality of error handling.

## Title:UI Stability – Resize the Browser
Bug ID: B006
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When resizing the browser the website page is not shirnking with the browser.
Steps to Reproduce:
    1. Open the Business Intelligence feature in a maximized browser window.
    2. Slowly resize the browser window horizontally from maximum width to minimum width.
    3. Observe the UI elements during resizing.
    4. Resize the browser window back to maximum width.
    5. Repeat steps 3-5, but resize vertically this time.
Expected Result:
    • During resizing, UI elements should adjust smoothly without flickering or jumping.
    • No UI elements should disappear unexpectedly during resizing.
Actual Result:
    • Currently this website is not compatible in mobile view.
Severity: Medium
Priority: High
Screenshot:
	
Additional Information: This issue affects the functionality of the page.

## Title:UI Stability – Navigate to different website page.
Bug ID: B007
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When resizing the browser the website page is not shirnking with the browser.
Steps to Reproduce:
    1. Navigate to the SOV Dashboard page.
    2. Navigate to the Keyword Tracker page.
    3. Click ‘<-’ or ‘Alt+<-’ to move backward to the SOV Dashboard page. 
    4. Verify whether the pages navigate correctly.
Expected Result:
    • The page should navigate to SOV Dashboard Page.
Actual Result:
    • The page is still on the current page.
Severity: High
Priority: High
Screenshot:
	



Additional Information: This issue affects the functionality of the navigating with different pages.

## Title:UI Stability – Navigate to different website page.
Bug ID: B008
Reporter: Yuvankumar L
Register Number: 20MIS0395
Date: August 2, 2024
Environment:
    • Platform: Zorin OS 17 Core
    • Browser: Firefox122.0 
    • URL: https://test.anarix.ai/market-intelligence?marketplace=amazon
Description: When entering the page number that exceeds the maximum page limit still it navigates to that page number. (eg., when the maximum page limit is 22, when i enter 100 in the goto section it navigates to the 100th page).
Steps to Reproduce:
    1. Navigate to the SOV Dashboard page.
    2. Ensure that all options are selected in all the filters (Keyword, Range, Position, Brand).
    3. Click the "Run" button.
    4. Verify that the data updated to show products related to the selected Frequency.
    5. Navigate to All Brand Coverage Section.
    6. Filter the brand that you need to view.
    7. Click the checkbox.
    8. Verify only the clicked checkbox is selected.

Expected Result: Only the clicked checkbox of the brand (napqueen) need to be turned on.
Actual Result: The checkbox of the All is turned on when we select the napqueen brand.
Severity: Medium
Priority: High
Screenshot:

Additional Information: This issue affects the functionality of the filter.


# Test Case Summary
## SOV Dashboard / Brand Analytics
    1. Keyword Filter
        ◦ ID: TC001
        ◦ Status: Pass
        ◦ Details: Keyword filtering works as expected, updating data to show products related to the selected keyword.
    2. Range Filter
        ◦ ID: TC002
        ◦ Status: Fail
        ◦ Details: The filter works for predefined ranges but fails to update correctly when using the "Custom Range" option.
    3. Position Filter
        ◦ ID: TC003
        ◦ Status: Pass
        ◦ Details: Position filtering updates the data correctly based on the selected position.
    4. Frequency Filter
        ◦ ID: TC004
        ◦ Status: Pass
        ◦ Details: Frequency filtering functions as intended, displaying data for the selected frequency.
    5. Pagination (Row Selection)
        ◦ ID: TC005
        ◦ Status: Pass
        ◦ Details: The page displays the correct number of rows as selected by the user.
    6. Pagination (Navigation)
        ◦ ID: TC006
        ◦ Status: Partial Pass
        ◦ Details: Page navigation works but allows navigation to non-existent pages beyond the maximum page limit.
## Keyword Tracker
    1. Add Keyword
        ◦ ID: TC007
        ◦ Status: Partial Pass
        ◦ Details: Keywords are added successfully, but the timing for added and updated keywords is incorrect.
          
    2. Add Bulk Keywords
        ◦ ID: TC007
        ◦ Status: Fail
        ◦ Details: Bulk keyword addition fails when the keyword limit is reached on Walmart. Additionally, the error message incorrectly mentions Walmart instead of Amazon.
    3. Change Keyword Status
        ◦ ID: TC008
        ◦ Status: Pass
        ◦ Details: Keywords can be activated or inactivated successfully.
    4. Delete Keyword
        ◦ ID: TC009
        ◦ Status: Pass
        ◦ Details: Keywords are deleted successfully from the tracker.
## UI and UX Quality
    1. UI Stability (Resize Browser)
        ◦ ID: TC010
        ◦ Status: Fail
        ◦ Details: The website is not compatible with mobile view and does not resize properly.
    2. UI Stability (Page Navigation)
        ◦ ID: TC011
        ◦ Status: Fail
        ◦ Details: Backward navigation between pages does not function correctly.
    3. Data Visualization
        ◦ ID: TC012
        ◦ Status: Pass
        ◦ Details: Charts and data visualizations are user-friendly and reflect the selected filters accurately.
## Cross-Browser Testing
    1. Compatibility with Different Browsers
        ◦ ID: TC013
        ◦ Status: Pass
        ◦ Details: The website functions correctly across different browsers but is not compatible with mobile view.


# Bug Summary

    1. Custom Range Filter
        ◦ ID: B001
        ◦ Severity: Low
        ◦ Priority: High
        ◦ Description: Selecting a custom date range does not update the data correctly.
    2. Pagination Goto Functionality
        ◦ ID: B002
        ◦ Severity: Low
        ◦ Priority: High
        ◦ Description: The Goto text field accepts page numbers beyond the maximum limit.
    3. Keyword Timing Issue
        ◦ ID: B003
        ◦ Severity: High
        ◦ Priority: High
        ◦ Description: Incorrect timing for added and updated keywords.
    4. Bulk Keyword Addition
        ◦ ID: B004
        ◦ Severity: Medium
        ◦ Priority: Medium
        ◦ Description: Bulk keyword addition fails on Walmart due to keyword limit.
    5. Bulk Keyword Addition (Amazon)
        ◦ ID: B005
        ◦ Severity: Low
        ◦ Priority: Medium
        ◦ Description: Incorrect error message mentions Walmart instead of Amazon.
    6. UI Stability (Resize Browser)
        ◦ ID: B006
        ◦ Severity: High
        ◦ Priority: High
        ◦ Description: Website does not resize properly and is not compatible with mobile view.
    7. Page Navigation Issue
        ◦ ID: B007
        ◦ Severity: High
        ◦ Priority: High
        ◦ Description: Backward navigation between pages does not function correctly.
    8. Checkbox Selection Issue
        ◦ ID: B008
        ◦ Severity: Low
        ◦ Priority: Low
        ◦ Description: Checkbox selection behavior is inconsistent, with "All" being selected instead of a specific brand.
# Conclusion
The testing revealed several areas for improvement, particularly in the range filter functionality, keyword addition timing, and UI stability. Addressing these issues will enhance the overall user experience and ensure the Business Intelligence feature functions as intended. The identified bugs should be prioritized and resolved promptly to improve the platform's reliability and usability.

# Prepared by: Yuvankumar L (20MIS0395)


