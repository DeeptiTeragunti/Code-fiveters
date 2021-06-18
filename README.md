# Code-fiveters
WIT-Hackathon-idea-submission 
Theme"Zero Hunger"
## Contents

- [Submission or project name](#submission-or-project-name)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Long description](#long-description)
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

###  SHORT DESCRIPTION
- # Whats the problem:
Food is one of the essential element and is consumed to provide nutritional support.Food loss is the bigger category, and incorporates any edible food that goes uneaten at any stage. Edible food is discarded at every point along the food chain in retail stores, in restaurants and at our own  houses.Households are responsible for the largest portion of all food waste.
Some of the negligence caused are overbuying Groceries as there are Sales on unusual products and promotions that encourage impulse and bulk food purchases at retail stores often lead consumers to purchase items that do not fit into their regular meal plans and, therefore, spoil before they can be used, About two-thirds of food waste at home is due to food not being used before it goes bad.
 A solution is definitely required to avoid wastage of food in large  number every day for a sustainable environment.
- # How can technology help: 
       Why not develop a one stop solution to stop wastage of food at our own houses as reducing food lost or wasted means more food for all, less greenhouse gas emissions, less pressure on environment, and increased productivity and economic growth.

- # The idea:
Food waste remainder application is the new norm. Its essential for every home.  From the user's point of view we provide an interface to calculate the amount of food/groceries being wasted for not noticing at the right time. We provide a platform the user to attach the grocery receipt or items which are left over which leads to a solution which analyzes the image and gives a detailed analysis of the quantity of food which was wasted in terms of money and a quick remainder to aler the user that the grocery would go bad in some days based on the shelf life.. It also recommends some of the recipies which can be done with the leftover food instead of wasting it.
# ![Architecture Diagram](./images/architecture-dgrm.png)

# Long Description
[long description](./DESCRIPTION.md)
The world is not on track to achieve Zero Hunger by 2030. If recent trends continue, the number of people affected by hunger would surpass 840 million by 2030.Food waste is a growing problem with increasing populations and issues through the value chain. It's estimated a staggering 32% of the food that we produce in the world goes to waste.Waste such as food scraps and yard waste usually easily ends up in landfills.We aim to reduce food waste with our idea and create a sustainable environment .


## Technology to the rescue
Technology has long been helping to hack world hunger. These days most conversations about tech’s impact on any sector of the economy inevitably involves artificial intelligence—sophisticated software that allows machines to make decisions and even predictions in ways similar to humans. Food waste tech is no different.


### What could our app do?
We built an app using python to scan the grcocery reciept of a user,Extract text details and analyse the expiry date of groceries and remind the user to use them before they go waste.

### Implementing Machine learning
These technologies range from machine vision that can spot when fruit is ready to be picked to algorithms that forecast demand in order to ensure users don’t overstock certain foods.In our app  we made use of ML code to predict if food is perishable or not using two parameters-moisture(in %) and temperature(in celcius). If the entered temperature is below 11°C the food is likely to get spoilt irrespective of it's moisture content. If the temperature is above 11 and the moisture content is below 15% then the food item may or may not be perishable. If the moisture content is above 15% and the temperature is above 11°C then the food is perishable. When the temperature is above 29°C the food would get spoilt irrespective of it's moisture content.

## Conclusion
It’s clear that waste reduction analytics is highly valuable to us. It has allowed us to utilize an under tapped resource: the produce data. Predicting what would expire soon and effective management og grocery at home could be a small step to solving the food waste issue.It would be a cost effective strategy to manage monthly expenses too.

 Finally, This app undoubtedly results in an environmental benefit and likely lead to Zero Hunger ensuring no food goes into the bin as well as no person stays hungry.


### Project Roadmap
The project currently does the following things:
Predict the persihables in the grocery 
Future Implementations would be 
- Scan the Grocery Reciept
- Predict Perishables based on input data
- Send  Reminder Notifications to the user 
- It's in a free tier IBM Cloud Foundry space. 

See below for our proposed schedule on next steps after Call for Code 2021 submission.

## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [Perishable-Classification.ipynb](./Perishable-Classification.ipynb)
- Run the ipynb file on a juptyter notebook
## Built with

- [IBM Cloud Pak](https://cloud.ibm.com/catalog?search=cloudant#search_results) - AI-powered software that can help organizations build, modernize, and manage applications securely across any cloud
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM Watson Studio]
## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ShejalShankar/shej28"><br /><sub><b>Shejal Shankar</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/DeeptiTeragunti"><br /><sub><b>Deepti Teragunti</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/Rakshitha-G-R"><br /><sub><b>Rakshita gr</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/hegdesahana"><<br /><sub><b>Sahana Hegde</sub></a><br /></td>
    
## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.


