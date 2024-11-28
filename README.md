# bench-runner-render (easy mode)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


## How to install quick-bench on render.com for free

Follow these steps :

1. Click on the render button above
2. Choose a blueprint name, for exemple "quickbench"
3. Click on "Create New Ressources"
4. Apply
5. Go to Dashboard > quickbench (your service name) > Environment
6. Copy your URL (purple link in header).
7. Past your URL as value for WEBHOOK_URL
8. Wait a minute for your instance to update
9. Enjoy !


This instance will be free for 90d, then you need to pay 7$/mo for the database.

Created by Jean-Michel Boulcourt. Inspired by ready4mars.

## Run Quick Bench or Build Bench locally

To launch Quick Bench, run `./quick-bench`. To launch Build Bench, run `./build-bench`.

A folder called `data` that contains cache data will automatically be created in the directory where the script is run.
