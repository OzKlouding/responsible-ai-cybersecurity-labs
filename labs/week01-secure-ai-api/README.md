# Week 01 – Secure AI API Deployment  

## 🎯 Objective
Deploy a simple **Azure OpenAI** (or AWS Bedrock) API securely using:  
- **Private Endpoints / VNet** integration  
- **Key Vault** for secrets  
- **API Management (APIM)** in front for rate limits & auth  

## 🛠️ Tools & Services
- Azure OpenAI / AWS Bedrock  
- Azure Key Vault  
- Azure API Management  
- Terraform or Bicep (optional)  
- Python (for testing API calls)  

## 📋 Steps
1. Provision Azure OpenAI resource (chat model).  
2. Create **Key Vault** and store API key.  
3. Deploy **APIM** and configure API endpoint.  
4. Restrict access with **Private Endpoint / NSG rules**.  
5. Test with Python `requests` using APIM URL + Key Vault secret.  

## ✅ Deliverables
- **Diagram:** Secure deployment flow (APIM → AI API → Private Endpoint).  
- **Terraform/Bicep file** (if IaC used).  
- **Python test script** (`test_api.py`) showing a secured call.  
- **Screenshot:** Successful API response.  

## 📖 References
- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)  
- [Azure API Management](https://learn.microsoft.com/en-us/azure/api-management/)  
- [Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/)  
