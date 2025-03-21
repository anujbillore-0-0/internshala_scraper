# **Internshala Internship Web Scraper**  

## **Overview**  
This project is a **web scraper** built using **Selenium** that extracts internship listings from **Internshala** based on specified **keywords**. The scraped data is stored in a **CSV file** with the following details:  

- **Title**  
- **Company**  
- **Location**  
- **Experience**  
- **Salary**  
- **Posted Time on Internshala**  

Additionally, the project includes a feature that **sends a WhatsApp message** to the user's number for each internship opportunity found in the CSV file.  

## **Features**  
- **Automated Data Scraping**: Uses Selenium to extract internships from Internshala.  
- **Custom Keyword Filtering**: Search for internships based on specific keywords.  
- **CSV Storage**: Saves internship details in a structured CSV file.  
- **WhatsApp Notification**: Sends real-time alerts for new internships via WhatsApp.  

## **Technical Stack**  

- **Python**  
- **Jupyter Notebook**
- **Chrome WebDriver**  
- **Selenium**  
- **Pandas**  
- **pyWhatKit**

## **Installation**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/internshala-scraper.git
   cd internshala-scraper
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
## **Usage**  

1. **Open Jupyter Notebook**  
   ```bash
   jupyter notebook
   ```

2. **Run the notebook**  
   - Open `internshala_scraper.ipynb`  
   - Execute the cells sequentially

3. **Check the generated CSV file**  
   - The scraped data will be saved in **internships.csv**  

4. **Send WhatsApp notifications**  
   - Execute the WhatsApp message cell in the notebook  

## **Customization**  
- Modify the **Username(Email)** and **Password** fields in the Login Section of Jupyter notebook 
- Modify the **keywords** in the notebook to filter internships based on your interests.  
- Adjust the **Number** in the WhatsApp message section to customize notifications.
  
## **License**  
This project is open-source and available under the **MIT License**.  
