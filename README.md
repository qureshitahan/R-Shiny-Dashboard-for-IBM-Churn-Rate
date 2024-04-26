**Summary**

**Task and Objective**
The objective of this endeavor is to develop a dashboard application tailored for the marketing, product development, and sales teams within a telecommunications company. This application harnesses customer churn data to furnish graphs and insights conducive to product refinement and the formulation of marketing strategies targeted towards customers exhibiting long-term loyalty. It also facilitates the creation of a sales strategy aimed at steering customers towards suitable products, thereby mitigating dissatisfaction and reducing churn.

**Data Background**
This initiative utilizes the Telecom Customer Churn dataset provided by IBM, designed for practicing data analysis on a business problem reflective of real-world scenarios. The dataset emulates a typical telecommunications company’s data repository, rendering the application’s utility extendable to actual datasets. With 7043 observations and 22 variables, the dataset encompasses customer demographics, service subscriptions, account details, and churn status.

**Approach / Methods Employed (Libraries)**
The raw dataset undergoes importation and cleaning within an R script housed in the "data" directory. The dashboard application is constructed using the R Shiny app package, leveraging the shinydashboard library for sidebar layout management. Graphical representations are crafted using ggplot2, while gridExtra facilitates the juxtaposition of graphs where necessary. Data filtering is accomplished through the filter function from the dplyr library.

**Outcomes**
The primary aim was to devise a dashboard application capable of elucidating customer churn data in a manner conducive to the comprehension of client distribution and churn rates across targeted demographics by marketing and sales teams. The outcome proved fruitful. Application users can filter customers based on various criteria such as gender, relationship status, dependency status, and senior citizenship. The dashboard then furnishes churn rates pertinent to the selected demographic, enabling businesses to discern demographic groups exhibiting elevated churn rates. Additionally, it provides insights into expenditure patterns and service preferences, presented through a comparative analysis of churned and retained clientele.
