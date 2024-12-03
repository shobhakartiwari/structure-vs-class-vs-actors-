
# Struct vs. Class vs. Actor in Swift

Swift provides three main types for handling data: **Struct**, **Class**, and **Actor**. Each has unique characteristics and use cases, making it essential to choose the right one for your specific needs. Below is a detailed comparison.

---

## Tabular Comparison

| Feature          | **Struct**                         | **Class**                          | **Actor**                             |
|-------------------|------------------------------------|-------------------------------------|---------------------------------------|
| **Type**         | Value type                         | Reference type                     | Reference type                        |
| **Memory Allocation** | Stack                          | Heap                                | Heap                                  |
| **Inheritance**  | Not supported                      | Supported                          | Not supported                         |
| **Initialization** | Memberwise initializers           | Custom initializers required       | Custom initializers required          |
| **Concurrency**  | Not inherently thread-safe         | Not inherently thread-safe         | Inherently thread-safe                |
| **Use Cases**    | Simple objects, immutable data     | Complex objects, mutable data      | Concurrent programming, mutable data  |

---

## Image Visualization

Below is an image that summarizes the differences:

![Struct vs. Class vs. Actor]([https://github.com/user-attachments/assets/6c6c321d-a270-4466-b727-d66102280b1a])

<img width="424" alt="Screenshot 2024-12-03 at 2 17 03 PM" src="https://github.com/user-attachments/assets/6c6c321d-a270-4466-b727-d66102280b1a">

---

## Key Takeaways

- **Struct** is ideal for lightweight and immutable data.
- **Class** is suitable for complex objects and scenarios requiring inheritance.
- **Actor** is a powerful choice for handling concurrent and mutable data safely in asynchronous programming.

### When to Use What:
- Use **Struct** for performance benefits with value types.
- Opt for **Class** when inheritance or identity is required.
- Consider **Actor** for thread-safe code in concurrent environments.

For more details, refer to Swift documentation.
