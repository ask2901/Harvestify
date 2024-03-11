# Harvestify
 
  <p align="center">
    <img alt="Supports Expo iOS" longdesc="Supports Expo iOS" src="https://github.com/ask2901/Harvestify/assets/109283594/2dcea52f-c40a-4be2-843e-839cb539223d" width="70%"/>
  </p>
</p>


## Features

- Developed a web application for disease detection and fertilizer prediction, with integrated e-commerce functionality
- Fully responsive front-end using Next.js and Tailwind CSS, and implemented the back-end using Node.js and Flask.
- Integrated a machine learning model ResNet-50 for disease classification, achieving 38+ disease class identification with
an 87,000+ image dataset. and accuracy of 96%
- Engineered a fertilizer recommendation system using a Naive Bayes classifier based on N-P-K and pH data
- I leveraged the Neurelo Data API to interface with MongoDB database, enabling efficient management of CRUD
operations and the linking of multiple databases

## Tech Stack 

- NextJs
- MongoDB
- Flask
- Python
- NodeJs
- Tensorflow

## 2. PLANT DISEASE CLASSIFICATION USING RESNET-9 
### **Description of the dataset 📝**
This dataset is created using offline augmentation from the original dataset. The original PlantVillage Dataset can be found here.This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.<br/>
### Libraries used
1. Numpy
2. Pandas 
3. Pytorch
<br/>
We have have use Pytorch here so it have 5 step life cycle<br/>
The five steps in the life-cycle are as follows:<br/>
1. Prepare the Data.
2. Define the Model.
3. Train the Model.
4. Evaluate the Model.
5. Make Predictions.

### Deep Learning Algorithm used- ResNet-9
In ResNets, unlike in traditional neural networks, each layer feeds into the next layer, we use a network with residual blocks, each layer feeds into the next layer and directly into the layers about 2–3 hops away, to avoid over-fitting (a situation when validation loss stop decreasing at a point and then keeps increasing while training loss still decreases). This also helps in preventing vanishing gradient problem and allow us to train deep neural networks. Here is a simple residual block:
<br/>

<img src="https://github.com/ask2901/Harvestify/assets/109283594/ef49a704-13e4-4581-86c6-88d36b39fa31" alt=""/>
<br/>
The accuracy of the model is 99.2%

## Screenshots

<img src="https://github.com/ask2901/Harvestify/assets/109283594/94dc62b0-a12a-41f4-89c3-124d4189a03d" width="45%">
<img src="https://github.com/ask2901/Harvestify/assets/109283594/4e51bb87-0b89-4f78-a19b-8266b3486495" width="45%">    <img src="https://github.com/ask2901/Harvestify/assets/109283594/0aca664b-e2df-44ca-a0e3-d2e0b3cb8395" width="45%">     <img src="https://github.com/ask2901/Harvestify/assets/109283594/d2e94942-8ef5-4980-b83c-b567d9d39810" width="45%">

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


## Thank You ❤️
