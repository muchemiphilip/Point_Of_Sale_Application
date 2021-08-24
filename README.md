# Point_Of_Sale_Application
This is a practical introduction to Kafka consumer API and you will be creating a typical consume-transform-produce pipeline using consumer APIs.

A POS (POINT OF SALE APPLICATION) in our case the pos-simulator, that generates a series of invoices and sends them to a Kafka topic.The Point of Sale validator (pos-validator) is a real-time validation service for invoices.
Its reading all invoices in real-time, apply some business rules to validate the invoice. If the validation passes it sends them to a Kafka topic valid_invoice_topic, if the validation failed send them to a kafka topic invalid_invoice_topic
