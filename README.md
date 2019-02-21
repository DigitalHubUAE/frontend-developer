# Frontend Developer Challenge

As a Frontend developer, we need more than making code to create pretty pages. So this test is going to be split into several sections with a different kind of challenges. You can choose whatever framework you fancy more but besides the framework, your code should be easily identified. 

For the API you can choose Python or NodeJS but need to have a GraphQL Interface. 


## First Challenge

Create a small GraphQL API to get Products and Categories using MongoDB, please also add at least 100 dummy data in the database so we can play around. There's plenty of libraries around to generate fake data. 

The product schema should be something similar like the one below.

```
Product {
  id, 
  sku,
  title, 
  url,
  abstract,
  description,
  price,
  image_url, 
  stock,
  category,
  created_at,
  updated_at,
}
```


#### Considerations
- Contain your API using Docker for Mongo and for the WebServer is a plus
- One line bash command to set up the project is a plus
- You can use the existent configuration on the internet to achieve this step
- Automated test for the API is a Plus

> Take on consideration before the creation of this step that the Challenge is going to consists in Frontend and Backend so you might want to split the repository in different folders, or having different repositories, it's completely up to you.


## Second Challenge

Now is time to create some frontend for our API. For this part, there is no specific requirement on technology but using React will be appreciated although Angular, Vue or others are also welcome. We don't try to overload with work so you can also go for solutions like Gatsby to speed up this step. 

As a result of this challenge, we should have a frontend with a Home Page listing all the categories.  When we click in a category we should be redirected to a landing page with all the products belonging to that category, lately, when you click in the product preview you should be redirected to the product page. 


#### Considerations

- We are not going to evaluate your design choices regarding colours and fonts, but we are going to take on considering how the overall experience is. 
- Again, don't waste time on the design


## Third Challenge

As modern developers, we understand that PWA is a good thing to see applied in every web. In this point, we are going to apply as many good practices we can but mostly focus on offline caching the products and categories content. 

At least we should be able to 

- Access offline to a previously visited content 
- Have a proper Manifest in place
- Cache all the static content


## Forth Challenge

Instead of waiting to have all the content before rending the page we should apply progressive loading. You can check this article about this point https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive/Loading


## Fifth Challenge

Test all the things. We are going to focus on functional tests.
We can use MochaJs or whatever else tool, but we need to be able to run all the tests headless from the command line. You can use docker for all the dependencies. 

## Lately 

Document the project, how to spin up the project, **how to run the tests** and how to generate the database and the dummy content. 

The README file should have all the step to set up the project locally. Remember as less command for setting up the project much better. 

After you have the documentation, create a repository in GitLab/Github/Bitbucket and send us the link of the repository to pablo.morales@mailmac.net

The time estimated for the project is between 2 and 8 hours if you feel that will take more you can cut corners, but that will affect the result of the test. Anyways you still have a complete week for finish the test after you received it.

We are going to give you feedback as fast as possible. 

