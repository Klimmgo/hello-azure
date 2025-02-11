# Azure Static Web App Demo  

Interactive website hosted on Microsoft Azure Static Web Apps with a physics-based rocket animation.  

## Features  
- Responsive design with CSS gradients  
- Interactive rocket physics simulation  
- Real-time mouse-controlled navigation  
- Automatic HTTPS deployment  

## Prerequisites  
1. GitHub account  
2. Microsoft Azure account (Free/Student tier recommended)  

## Deployment  
1. **Fork this repository**  
2. **Connect to Azure Static Web Apps**:  
   - Navigate to [Azure Portal](https://portal.azure.com)  
   - Create Static Web App resource → Link your GitHub repo  
   - Configure build settings:  
     - App location: `/`  
     - Output location: *leave empty*  
3. **Access live site**:  
   `https://[your-app-name].azurestaticapps.net`  

## Technologies  
- HTML5 Canvas-free animation  
- CSS3 Custom Properties  
- RequestAnimationFrame API  
- Azure Global CDN  

## License  
MIT License - Free for modification/commercial use  
