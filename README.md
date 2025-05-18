<h1>Vanich</h1>
An E-commerce web app for people. The website aims to support freelance works and local products in order to increase people's incomes.
Vanich version 1.0.0 only has 6 functional pages: 

1. Home (https://localhost:3000),
2. Product (https://localhost:3000/product),
3. Product details (https://localhost:3000/product/detail/[id]),
4. Job (https://localhost:3000/job),
5. Job details (https://localhost:3000/job/detail/[id]), and
6. Register (https://localhost:3000/register).


<h2>How to run the code in local environment</h2>


1. Download the branch named "forLocal".
2. Open it on VScode and open terminal. Make sure you are on the directory Vanich that has "docker-compose.yaml" file.
3. (Need to install colima first) [If you use colima to run Docker, do this step. Docker Desktop works fine but I use macOS and I can't open Docker Desktop] write command "<b>colima start</b>"
4. "<b>docker-compose build</b>"
5. "<b>docker-compose up -d</b>"
6. Then, open <a>https://localhost:3000</a>. You will see the home page of Vanich. In case the page was not loaded, change DEBUG to True in /backend/core/settings.py (DEBUG = True).


***After finish running you need to "<b>docker-compose down</b>" and "<b>colima stop</b>" to stop all services.***
