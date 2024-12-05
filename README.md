<!-- This repository contains a README file sample for Daytona Samples and the MIT License.

It can be used as a template to create sample repositories that can be added into [Daytona](https://github.com/daytonaio/daytona).

Once you finish your sample and it gets merged, you can open a PR in the Daytona repo and submit the sample into the [index file](https://github.com/daytonaio/daytona/blob/main/hack/samples/index.json). -->

# Sample <NodeJS/React>

TerraGrow is an intelligent web app that uses a Random Forest model for crop recommendations and the Llama3-8b-8192 model from Groq to suggest yield improvement strategies. By analyzing factors like nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, and pH, it provides data-driven insights to help farmers optimize planting decisions and achieve higher yields.

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/Subash-Lamichhane/TerraGrow-daytona
   ```  

3. **Add 3000 as forwarded ports.**
3. **Set up the environment variables by creating a ```.env``` file in the backend directory and add given details:**: 
   ```bash  
   PORT=3000
   GROQ_API_KEY=<YOUR_GROQ_API_KEY>
   ```  

4. **Start the Application**:  
   Navigate to backend folder 
      ```bash  
      npm start
      ```  
   Navigate to frontend folder 
      ```bash  
      npm run dev
      ```  


## ✨ Features  

<!-- List of sample features (e.g. realtime chat app, standardized development environment with devcontainers) -->
- **Smart Crop Recommendations**  
  Utilizes Random Forest models to suggest the best crops based on environmental data like NPK levels, temperature, humidity, and pH.

- **Yield Improvement Suggestions**  
  Powered by the Llama3-8b-8192 model from Groq, it provides actionable strategies to boost crop yield, such as nutrient adjustments and irrigation optimization.

- **User-Friendly Interface**  
  Offers an intuitive platform for inputting data and accessing tailored recommendations effortlessly.

- **Precision Agriculture Made Simple**  
  Enhance efficiency and sustainability by aligning crop choices and yield strategies with specific conditions.

## Demo
![Usage](https://github.com/user-attachments/assets/22574a79-71ca-4eed-af90-d2a46475ff7c)
