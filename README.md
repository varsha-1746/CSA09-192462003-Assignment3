# CSA09 – Assignment 3 (CO3): Exception Handling & Multithreading

- **Student Name:** Fathi Muthu Johara M
- **Register Number:** 192411009
- **Assigned Role:** Student B (Testing, Benchmarking, Experimental Tables & Stack Traces)
- **Repository:** `CSA09-192411009-Assignment3`

## Project Structure

| Package | Problem Title | Key Concepts Demonstrated |
| :--- | :--- | :--- |
| `src/Q1` | `BankAtmSimulation.java` | Checked vs. Unchecked exceptions, multi-catch, catch-order hierarchy, `finally` cleanup |
| `src/Q2` | `OnlineExamPortal.java`, `StorageDemo.java` | Custom checked exceptions, 3-layer propagation, exception chaining (`getCause()`) |
| `src/Q3` | `LogPipeline.java` | `AutoCloseable`, try-with-resources, reverse-order closing, `getSuppressed()` |
| `src/Q4` | `RideDispatchSystem.java` | `Thread` vs. `Runnable`, thread states (`NEW`–`TERMINATED`), priorities, daemon threads |
| `src/Q5` | `TicketBookingBenchmark.java` | Race conditions, `synchronized` method/block, `ReentrantLock`, `AtomicInteger` CAS |
| `src/Q6` | `OrderProcessingPipeline.java` | Deadlock simulation (`ThreadMXBean`), global lock ordering, `wait()` / `notifyAll()` |
| `src/Q7` | `BatchLogProcessor.java` | `ExecutorService` fixed thread pool, `Callable` & `Future`, fault isolation, scaling |