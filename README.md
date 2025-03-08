# 📌 Queue Line System (clsQueueLine) ⚡

> **A C++ queue-based ticketing system that manages customer queues efficiently with real-time ticket tracking and service estimation. 🚀**

---

## 🌟 Project Overview

The `clsQueueLine` class implements a **queue-based ticketing system** using C++. It allows customers to take tickets, tracks the waiting list, and provides estimated service times. The system maintains a queue of tickets and offers functionalities to serve customers in order.

### 🔹 Core Functionalities:
- **Issue Tickets with Unique Numbers** 🎫
- **Track Waiting Clients & Served Clients** 📊
- **Estimate Service Time for Each Client** ⏳
- **Serve Clients in First-Come-First-Served (FCFS) Order** ⚡
- **Display Queue Information & Ticket Details** 📜
- **Print Ticket List in Left-to-Right or Right-to-Left Order** 🔄

This system is **useful for service counters, customer support centers, and any application requiring queue-based management**.

---

## ✨ Features

### 🔹 Ticket Management
- **`IssueTicket()`**: Generates a new ticket with a unique number.
- **`WhoIsNext()`**: Returns the next client to be served.
- **`ServeNextClient()`**: Removes the next client from the queue.

### 🔹 Queue Tracking
- **`WaitingClients()`**: Returns the number of clients still waiting.
- **`ServedClients()`**: Returns the number of clients already served.
- **`PrintInfo()`**: Displays queue statistics, including total, waiting, and served clients.

### 🔹 Ticket Display
- **`PrintTicketsLineRTL()`**: Displays the ticket queue from right to left.
- **`PrintTicketsLineLTR()`**: Displays the ticket queue from left to right.
- **`PrintAllTickets()`**: Prints detailed information for all tickets in the queue.

---

## 🚀 How It Works

### 🔹 Issuing & Serving Tickets
- Customers take a ticket using `IssueTicket()`.
- The system assigns a **unique ticket number** prefixed by a given identifier (e.g., "A0").
- Clients are served in order using `ServeNextClient()`.

### 🔹 Tracking Queue Status
- `WaitingClients()` returns the number of clients still in line.
- `ServedClients()` keeps track of those who have been attended to.
- `PrintInfo()` displays an overview of the queue’s status.

### 🔹 Ticket Display Order
- `PrintTicketsLineRTL()` prints the queue from newest to oldest.
- `PrintTicketsLineLTR()` prints the queue from oldest to newest.
- `PrintAllTickets()` provides detailed ticket information.

---

## 📚 Potential Enhancements

- 🔄 **Priority Queue Support**: Implementing different service priorities.
- 📌 **Multi-Counter Support**: Managing multiple service queues.
- 📊 **Graphical User Interface (GUI)**: Building an interactive UI for better usability.
- 🌐 **Database Integration**: Storing ticketing data persistently.

---

## ⚙️ Technologies Used

- **Language**: C++
- **Queue Data Structure**: Manages customer tickets.
- **Stack Data Structure**: Used for alternative ticket tracking.
- **Dynamic Memory Management**: Efficiently stores and processes ticket information.

---

## 🎯 Learning Outcomes

This project demonstrates:
- ✅ **Queue operations (enqueue, dequeue, tracking)**
- ✅ **Real-world queue-based ticketing systems**
- ✅ **Customer management & service time estimation**
- ✅ **Efficient queue traversal and display methods**

---

## 📜 License

This project is **open-source**. Feel free to modify and enhance it! 🚀

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for improvements, submit a Pull Request.

---

## 🏁 Ready to Explore?

### 🚀 How to Run
1. **Download** the repository.
2. **Include** `clsQueueLine.h` in your project.
3. **Compile & Run** your C++ program with a standard compiler (e.g., `g++ main.cpp -o output`).
4. **Test** different queue operations.

