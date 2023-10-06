# Injecting the Logging Service into Components
01. Angular's dependency injector injects an instance of our service into our component
02. You let angular know you need it by passing it in your constructor
03. constructor(private loggingService: LoggingService)
04. It must also be imported
05. Also must add a providers property to the component decorator
06. providers: [LoggingService]