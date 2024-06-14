## Backend Interview Task

---

### Implementing Configurable Error Logging in NestJS

**Scenario:**

You are required to implement a logging system in a NestJS application that allows switching between different logging implementations based on an environment variable. The system should use dependency injection to manage these implementations.

**Task:**

1. **Interface Definition:**

   - Define an interface `ILogger` with a single method `logError`.

2. **Concrete Implementations:**

   - Implement at least two concrete classes that adhere to the `ILogger` interface. For example, `ConsoleLogger` and `FileLogger`.

3. **Dependency Injection:**

   - Set up these implementations to be injected into the application at startup.
   - Use an environment variable to determine which implementation should be used.

4. **Configuration:**

   - Demonstrate how the application can switch between these implementations based on the value of the environment variable.

5. **Testing:**
   - Set up a unit test framework of your choice (e.g., Jest).
   - Write unit tests to verify the behavior of your logging implementations and the configuration logic.

**Expectations:**

- **Clean Code:** Ensure your code is clean, well-organized, and adheres to best practices.
- **Good Commit Pattern:** Follow a clear and logical commit pattern.
- **Accurate Implementation:** The implementation should meet the requirements accurately.
- **Testing:** Show how the implementation can be tested, and provide example tests.

**Deliverables:**

1. Source code with the interface and implementations.
2. Configuration setup demonstrating environment-based switching.
3. Unit tests for the implementations and configuration logic.
4. A brief documentation of your thought process and any assumptions made.

**Time Frame:**

You have about 12 hours from task reception to complete this task.
