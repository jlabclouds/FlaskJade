# Flask Jade

FlaskJade is a lightweight starter project for building web applications using [Flask](https://flask.palletsprojects.com/) and Jade (now known as [Pug](https://pugjs.org/)) templating. This setup is ideal for:

FlaskJade is well-suited for a variety of scenarios where simplicity, speed, and maintainability are important. Some of the key benefits and use cases include:

- **Rapid prototyping** of web apps with clean, readable templates.  
    FlaskJade allows developers to quickly scaffold new projects and iterate on ideas without the overhead of complex configurations. The use of Jade/Pug templating makes it easy to write concise, maintainable HTML, enabling faster UI development and experimentation.

- **Educational projects** to learn Flask and template rendering.  
    The project structure is intentionally minimal, making it ideal for beginners who want to understand the core concepts of Flask, routing, and template rendering. By working with Jade/Pug, learners also gain exposure to modern templating practices used in many production environments.

- **Small to medium web applications** where simplicity and quick iteration are priorities.  
    FlaskJade is perfect for projects that do not require the complexity of larger frameworks. Its lightweight nature ensures that developers can focus on building features rather than managing boilerplate code or configuration.

## Best Use Cases

FlaskJade excels in the following scenarios:

- **Building dashboards, admin panels, or internal tools:**  
    The combination of Flask’s flexibility and Jade/Pug’s clean syntax makes it easy to create user interfaces for managing data, monitoring systems, or performing administrative tasks.

- **Creating proof-of-concept or MVP web applications:**  
    When you need to validate an idea or demonstrate functionality to stakeholders, FlaskJade provides a fast path from concept to working prototype, allowing for quick feedback and iteration.

- **Learning or teaching Flask and template-driven web development:**  
    The straightforward project layout and use of modern templating make FlaskJade an excellent resource for workshops, tutorials, or self-guided learning.

- **Developing small-scale production apps:**  
    For applications with limited scope or user base, FlaskJade offers a maintainable and efficient foundation without unnecessary complexity.

- **Experimenting with new features or integrations:**  
    Developers can use FlaskJade as a sandbox for testing new libraries, APIs, or frontend components in a controlled, easy-to-understand environment.

## Getting Started

Follow these steps to set up and run the project:

1. **Create a virtual environment:**
    ```bash
    python3 -m venv .venv
    ```

2. **Activate the virtual environment:**
    ```bash
    . .venv/bin/activate
    ```

3. **Install Flask:**
    ```bash
    pip install flask
    ```

4. **Upgrade pip (optional but recommended):**
    ```bash
    python3 -m pip install --upgrade pip
    ```

5. **Run the Flask application:**
    ```bash
    flask --app __init__ run
    ```

Your FlaskJade app should now be running locally. Open your browser and navigate to `http://127.0.0.1:5000/` to view it.

---

For more information on Flask, see the [official documentation](https://flask.palletsprojects.com/).