# 3-Tier Architecture Using Docker Compose 

In this setup, we'll be using Docker Compose to orchestrate a 3-tier architecture comprising WordPress, MySQL, and a custom network for communication between the containers.


### WordPress Container

The WordPress container hosts the WordPress application, serving as the front-end interface for managing website content. It depends on the MySQL database container for storing and retrieving data.

### MySQL Database Container

The MySQL database container stores all the application data. It's responsible for managing databases, tables, and user access permissions.

### Deployment Instructions

1. Ensure you have Docker Compose installed on your system.
2. Create a directory for your project and create a `docker-compose.yml` file inside it.
3. Copy and paste the contents of the `docker-compose.yml` file provided.
4. Open Terminal: Open a terminal window and navigate to your project directory.

5. Start Containers: Run the following command to start the containers:
    ```
    docker-compose up -d
    ```

6. Access WordPress Application: Once the containers are up and running, access the WordPress application by navigating to [http://localhost:8080](http://localhost:8080) in your web browser.

### Notes

- Security: Ensure to replace placeholder passwords (`12345678`, `Mysql`) with secure ones for production use.
  
- Customization: Customize container names, network configurations, and volume mounts as needed to suit your project requirements.
  
- Advanced Configurations: Explore Docker Compose documentation for more advanced configurations and optimizations.
  
- Feedback and Contributions: Feel free to contribute or report issues on [GitHub](https://github.com). Your feedback is appreciated!

Now, let's deploy your Docker Compose 3-Tier Architecture and start building your WordPress website!

### Contact Us 📧

Have questions, feedback, or need assistance? Reach out to:

Email: hrushikeshdagwar@gmail.com
