<h1 class="toc">Call Display on the Account Page</h1>

The Adapter comes with a Visualforce Page that displays all phone calls
made using Amazon Connect for an Account. It differs from thee standard
Activity Related List because if filters all other activities out and
focuses on the phone calls only.

To show the recent calls on the Account details page, add the
"ACSFCCP_CallLogging_View" Visualforce Page to the Account Page layout.
It is recommended to create a dedicated section with a 1-Column layout
for this purpose, and to make the Visualforce Page scrollable.

1.  Log in to your Salesforce Org

2.  Navigate to **Setup** then in type *Object Manager* in Quick Find

<img src="../media/image203.png" />

3.  Click on the "Account" object

<img src="../media/image208.png" />

4.  Click on the "Page Layouts"

<img src="../media/image209.png" />

5.  Click on the "Account layout" and the layout designer will open

<img src="../media/image210.png" />

6.  From the left-hand side menu, select "Fields"

<img src="../media/image211.png" />

6.  Drag and Drop "Section" item to add a new section on the layout

<img src="../media/image212.png" />

<img src="../media/image213.png" />

8.  On the pop-up form, set Section Name ("Call Logging View") and 1-Column Layout

<img src="../media/image214.png" />

9.  Click "OK"

<img src="../media/image215.png" />

10. From the left-hand side menu, select Visualforce Pages:

<img src="../media/image216.png" />

11. Drag and drop "ACSFCCP_CallLogging_View" item to the "Call Logging View" section

<img src="../media/image217.png" />

<img src="../media/image218.png" />

<img src="../media/image219.png" />

12. Hover the newly added component and click on the "Setting" icon

<img src="../media/image220.png" />

Check "Show scrollbars" and click "OK"

<img src="../media/image221.png" />

13. Click the "Save" button in the top-left corner

<img src="../media/image222.png" />

14. Make some phone calls, ask to speak with an agent. Open the Account, then select "Details" tab

<img src="../media/image223.png" />

15. Scroll down the Details page until you see the "Call Logging View" section

<img src="../media/image224.png" />

For more information on how to add a Visualforce Page to a Page layout,
please visit:

[https://trailhead.salesforce.com/en/modules/visualforce_mobile_salesforce1/units/visualforce_mobile_salesforce1_layouts_cards](https://trailhead.salesforce.com/en/modules/visualforce_mobile_salesforce1/units/visualforce_mobile%20_salesforce1_layouts_cards)
