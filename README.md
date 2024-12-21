---

# IT-Company-Website  

## Overview  

The “IT Company Website” is a modern, responsive website designed using HTML, CSS, Bootstrap, and JavaScript. It is optimized to function seamlessly across all devices, ensuring an excellent user experience. The website is tailored for an IT company offering services in **School Management Systems**, **Document Management Systems**, and **Data Recovery Solutions**.  

### Key Features  
- **School Management Systems**: Simplified tools for managing academic institutions, including student records, attendance, and performance tracking.  
- **Document Management Systems**: Secure and efficient solutions for storing, organizing, and retrieving documents digitally.  
- **Data Recovery Solutions**: Advanced services to recover lost or corrupted data across multiple platforms.  

### Website Modules  
The website includes the following modules to provide comprehensive information and functionality:  
- **About**: Learn about the company's mission, vision, and values.  
- **Services**: Detailed descriptions of all IT solutions offered.  
- **Portfolio**: Showcase of past projects and accomplishments.  
- **Team**: Meet the skilled professionals behind the company.  
- **Career**: Opportunities to join the team, with an integrated application form.  
- **Contact**: Easy-to-use contact form for inquiries.  
- **FAQ**: Answers to common questions for better user understanding.  

### Email Notification System  
Whenever a user submits the **Contact** or **Career** form, an email notification is sent to the company’s designated email address. This ensures timely communication and efficient follow-up.  

---

## Deployment  

### Website Link  


### Note for Deployment  
1. **PHP Mailer**:  
   - The PHP Mailer feature is currently non-functional on the deployed version. To enable this feature:  
     - Download the project and run it locally using XAMPP or WAMP.  
     - Configure the sender's credentials in the `mailing/mailingvariables.php` file.  
     - Specify the receiver's email address in the `contactme.php` and `careers.php` files.  
     - Ensure the path to the `tmp-uploads` folder is set correctly in the `careers.php` file for file uploads.  

2. **Local Setup**:  
   - Clone the repository.  
   - Set up a local server environment using XAMPP or WAMP.  
   - Import the database if required for additional functionality.  

---

## Contributing  
We welcome contributions to enhance the website's functionality and design. Please submit a pull request with detailed information about your proposed changes.  

---

## License  
This project is licensed under the MIT License.  

---

