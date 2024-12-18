Case Study to understand Azure Functions and Azure Queue Storage

Constraints:
- Use only the following Azure services:
    - Virtual Machines (VMs) for compute tasks.
    - Function Apps for serverless business logic.
    - Blob Storage for unstructured data.
    - Queue Storage for task queuing.
    - Table Storage for structured data.

Scenario: Task Queue with Azure Queue Storage
You’re part of a logistics company, QuickShip. The company needs a system to process incoming shipment requests. Each request is placed in a queue, and a background process handles them one by one to ensure no request is missed. Your manager has asked you to implement a system using Queue Storage and Function Apps to automate this task processing. You need to ensure it scales during peak hours when shipment requests flood in.