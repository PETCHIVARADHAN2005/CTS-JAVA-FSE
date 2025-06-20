Purpose:
Ensures that a class has only one instance and provides a global point of access to it.

Used In:
SingletonPatternExample.java

Technical Highlights:

Implements lazy initialization.

Uses a private constructor and a static method (getInstance()).

Useful for cross-cutting concerns like logging, configuration, or database connection management.

Benefits:

Prevents resource conflicts by using a single instance.

Provides consistent logging across the application.