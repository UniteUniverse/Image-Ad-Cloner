# Image-Ad-Cloner

A ready-to-use **n8n template** that turns a competitor ad into a high-quality, **brand-swapped creative** for your product.  
Users upload their product image and paste a competitor ad URL; the workflow extracts both images, builds a detailed **image-generation prompt** (handles partial on-image text, labels, and multiple packages), and calls a generative image model to produce a new ad that matches the competitor’s style while featuring your own packaging and copy.

## How It Helps

- Rapidly create polished ad variations from top-performing competitor creatives  
- Automates image extraction, Base64 conversion, and prompt construction  
- Enables non-designers to generate consistent, high-quality ads  
- Designed for fast creative iteration inside n8n  

## How It Works 
📂 **Demo & Setup Guide:**  
[Click here to view the Google Drive file](https://drive.google.com/file/d/1PLFPHSXQ-DaNAKeBQv7G9SzaXT0c3hRt/view?usp=sharing)

1. User submits a form with:
   - Competitor ad image URL  
   - Product image  

2. The workflow:
   - Downloads and converts images into inline data  
   - Builds a precise image-generation prompt  
   - Detects and replaces on-image text, labels, and packaging  
   - Sends the final prompt to the image generation model  

3. Returns the generated ad image, ready for review and download  

## Best For

- Facebook and Instagram ad teams running A/B tests  
- E-commerce brands creating on-brand ad variations quickly  
- Agencies generating multiple creatives from a single competitor reference  

## Important Notes

- Requires credentials for the generative image API (configured in the template)  
- Ethical and legal considerations:
  - Ensure you have the right to use or adapt competitor assets  
  - Avoid trademark or copyright infringement  
  - Always review final creatives before running ads  
