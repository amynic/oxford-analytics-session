# Student Exercise

## Power BI and AI Builder

*(Same storyline from session continued…)*

Tailwind Traders are DIY, Home and Garden store in and around the London area. The COVID19 pandemic has really shook up the business and priorities, they need deeper insight into where to focus precious time, money, and resources in investing in their future. Tailwind traders have employed us as their data science consultant team to help them form a data driven plan for the next financial year.

After the initial feedback sessions sharing the Google Activity data by London Borough, possible IoT architecture solutions and AI solutions that support operational efficiency and future predictions - the Tailwind Traders team have funded another round of consultancy and investigation work. This time they want to focus on marketing efforts - how do they gain net new customers.

One option, as they are based primarily in London, is they want to get in front of new customers whilst they are travelling about their busy days and take a break by stepping into a store or browsing online.

As the new Data Science lead on the project you are tasked with:

### Task 1:
Explore the [Public Transport Journeys by Type of Transport - London Datastore](https://data.london.gov.uk/dataset/public-transport-journeys-type-transport) open dataset to understand types of journeys people are making around London using Power BI

* **What you need to do:**
    * Dataset is open data and available here: [Public Transport Journeys by Type of Transport - London Datastore](https://data.london.gov.uk/dataset/public-transport-journeys-type-transport)
    * Bring that data into Power BI as another dataset [into the current Power BI findings](https://github.com/amynic/oxford-analytics-session/blob/main/section-1/section1-powerbi-dataexploration.pbix)
    * Investigate the data, share **3 insights** you learnt from the dataset and **2 project recommendations** Tailwind Traders could work on
 
*  **Learning Resources to help you:**
    * Download Power BI Desktop (Windows Only) [Power BI Desktop—Interactive Reports | Microsoft Power BI](https://powerbi.microsoft.com/en-gb/desktop/)
    * Power BI Learning Path: [Create and use analytics reports with Power BI - Learn | Microsoft Docs](https://docs.microsoft.com/en-us/learn/paths/create-use-analytics-reports-power-bi/)
    * Documentation for Power BI: [Power BI documentation - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/)
    * Use the forums to find answers to questions on 'How to do X in Power BI' [Forums - Microsoft Power BI Community](https://community.powerbi.com/t5/Forums/ct-p/PBI_Comm_Forums)
 
 
### Task 2:
Add a new page to the Power BI report shared with Tailwind Traders Business Stakeholders in round one of investigations

* **What you need to do:**
    * Add a new page to the [Power BI Business Stakeholders report](https://github.com/amynic/oxford-analytics-session/blob/main/section-2/section2-powerbi-report.pbix)
    * Keep consistency within the report and add your **3 insights** to tell the story to the business
 
* **Learning Resources to help you:**
    * Power BI Report Design Learning Path: [Design effective reports in Power BI - Learn | Microsoft Docs](https://docs.microsoft.com/en-us/learn/paths/power-bi-effective/)
    * Documentation for Power BI: [Power BI documentation - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/)
    * Guy in a Cube YouTube Channel: [Guy in a Cube - YouTube](https://www.youtube.com/channel/UCFp1vaKzpfvoGai0vE5VJ0w)
 
 
### Task 3:
Recreate the **forms recognizer solution** for analysing Tailwind Traders receipts and invoices with no-code using AI Builder and build this functionality into a Power App

* **What you need to do:**
    * Use the datasets available here to train your invoice model: [training](https://globaleventcdn.blob.core.windows.net/assets/aiml/aiml10/data/training.zip)/[testing](https://globaleventcdn.blob.core.windows.net/assets/aiml/aiml10/data/test.zip)
    * Use AI Builder to create a forms recognizer model to understand Tailwind Trader Invoices
    * Test your model with **3 different test invoices** provided
    * Publish your model within AI Builder
    * **Build your Invoice Model** into a Power App:
        * Where a Tailwind Traders employee can take a picture/upload an invoice
        * The invoice gets analysed by your AI Builder model and extracts all data from the invoice
        * Saves the invoice data digitally in a simple table
    * Test your app on new data. Record the screen running through your application and showing each step above is completed
 
* **Learning Resources to help you:**
    * Get Started with AI Builder Learning Path: [Get started with AI Builder - Learn | Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/get-started-with-ai-builder/)
    * Process Custom Forms with AI Builder: [Process custom forms with AI Builder - Learn | Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/get-started-with-form-processing/)
    * Use Forms Recognizer Model in Power Apps: [Use the form processor component in Power Apps - AI Builder | Microsoft Docs](https://docs.microsoft.com/en-us/ai-builder/form-processor-component-in-powerapps)


***Advanced (optional):** explore https://api.tfl.gov.uk to see if you can connect any further transport and activity patterns around London for Tailwind Traders*