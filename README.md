FlyChatter

FlyChatter is an intelligent, automated flight search assistant designed as a WhatsApp bot. Built using the .NET Aspire stack, this project provides a seamless way for users to search for real-time flight availability and pricing directly through WhatsApp, eliminating the need to browse multiple travel websites.

# Key Features

    WhatsApp Integration: Search for flights effortlessly using a familiar, user-friendly messaging interface.

    Microservices Architecture: Powered by .NET Aspire, ensuring high scalability and efficient service communication.

    Real-time Data: Integration with major travel APIs (Travelpayouts/Kiwi Tequila) to fetch up-to-date flight schedules and competitive pricing.

    Intelligent Routing: Automated handling of departure/destination requests to provide accurate search results.

    Robust Backend: Built with ASP.NET Core Web API, following clean architecture principles for maintainability.

# Tech Stack

    Framework: .NET 9, .NET Aspire

    Language: C#

    Architecture: Microservices, Clean Architecture

    Integrations: WhatsApp API (Twilio or similar provider), Travelpayouts/Kiwi Travel APIs

    Development Environment: VS Code, Ubuntu/Linux, Docker

# How It Works

    User Input: The user sends a message to the FlyChatter WhatsApp number with details (origin, destination, date, and budget).

    Processing: The bot captures the intent and forwards the request to the FlyChatter backend service.

    API Retrieval: The service queries external travel APIs to find the best-matched flight deals.

    Response: The bot delivers a curated list of flight options back to the user within the WhatsApp chat.

# Status

This project is currently under active development.
