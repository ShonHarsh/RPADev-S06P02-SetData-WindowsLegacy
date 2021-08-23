![](https://shonharsh.github.io/curriculum-vitae/images/uipath-logo.png)

# S06P02 Set Data

This project is my solution in **C#** to the **Set Data** practice found in section 06 practice 02 of the UiPath - RPA Developer Foundation course.

### Getting Started

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output pane.

### Details

**Course:** UiPath - RPA Developer Foundation

**Section:** 06 Selectors

**Practice:** 02 Set Data

**GitHub:** https://github.com/ShonHarsh/RPADev-S06P02-SetData

Sample Output

```
08/13/2021 16:20:10 => [Debug] Execution started for project: RPADev-S06P02-SetData
08/13/2021 16:20:12 => [Info] RPADev-S06P02-SetData execution started
08/13/2021 16:21:07 => [Info] Audit: Using Web App. Browser: Chrome URL: http://www.rpachallenge.com/
08/13/2021 16:21:57 => [Info] RPADev-S06P02-SetData execution ended in: 00:01:45
```

### Notes

The robot reads a Microsoft Excel spreadsheet produced in the previous practice.  It also uses Google Chrome.

Regarding the name field, the data scraped from the website in the previous section had some wonky text encoding or characters for the spaces.  This caused issues with the indexOf(" ") not matching.  I replaced the troublesome character with spaces in the source file.

### RPA Developer Foundation Sections

1. Get Started With RPA Development

2. Variables, Data Types And Control Flow In Studio

   P01 [RPADev-S02P01-ForEachIfStatement](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement)

   P02 [RPADev-S02P02-GenericValue](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue)

   P03 [RPADev-S02P03-Switch](https://github.com/ShonHarsh/RPADev-S02P03-Switch)

3. Data Manipulation In Studio

   P01 [RPADev-S03P01-Lists](https://github.com/ShonHarsh/RPADev-S03P01-Lists)

   P02 [RPADev-S03P03-Dictionaries-Integers](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers)

   P03 [RPADev-S03P04-Dictionaries-Doubles](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles)

   P04 [RPADev-S03P05-InputValidation](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation)

   P05 [RPADev-S03P06-ReplacingPlaceholders](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders)

   P06 [RPADev-S03P07-ExtractEmailAddress](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress)

   P07 [RPADev-S03P08-ExtractEmailAddressRegEx](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx)

4. Excel And Data Tables With Studio

   P01 [RPADev-S04P01-CalculatingSums](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums)

   P02 [RPADev-S04P02-CalculatingLossInvoices](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices)

   P03 [RPADev-S04P03-CalculatingPercentagesOfExpenses](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses)

5. UI Automation With Studio

   P01 [RPADev-S05P01-PasswordGenerator](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator)

   P02 [RPADev-S05P02-TheRPAChallenge](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge)

   P03 [RPADev-S05P03-InputActions](https://github.com/ShonHarsh/RPADev-S05P03-InputActions)

   P04 [RPADev-S05P04-OutputActions](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions)

   P05 [RPADev-S05P05-DataScraping](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping)

6. Selectors In Studio

   P01 [RPADev-S06P01-GetAndSortData](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData)

   P02 [RPADev-S06P02-SetData](https://github.com/ShonHarsh/RPADev-S06P02-SetData)

   P03 [RPADev-S06P03-Highlight-TypeItems](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems)

7. Project Organization In Studio

   P02 [RPADev-S07P02-StateMachines](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines)

   P03 [RPADev-S07P03-FixMyWorkflow](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow)

   P04 [RPADev-S07P04-Libraries](https://github.com/ShonHarsh/RPADev-S07P04-Libraries)

8. Error And Exception Handling In Studio

9. Debugging In Studio

10. PDF Automation In Studio

11. Email Automation With Studio

12. Orchestrator For RPA Developers

13. Robotic Enterprise Framework Overview

### Requirements

[UiPath Studio](https://www.uipath.com/product/studio) is required to run the robot.

### Git Notes

Clone the project to develop or change it.

`git clone https://github.com/ShonHarsh/RPADev-S06P02-SetData`

### Links

[UiPath: Automation Platform](https://www.uipath.com/)

[UiPath Studio](https://www.uipath.com/product/studio)

[My Website](https://shonharsh.github.io/curriculum-vitae/index.html) - Errors, spelling fixes and comments are very welcome!

