# Top 60 WebSocket Interview Questions

## 1. WebSocket Fundamentals

1. What are WebSockets, and why are they used?
2. How do WebSockets work internally?
3. What is the difference between WebSockets and HTTP?
4. What is the difference between WebSockets, short polling, and long polling?
5. What is a full-duplex connection?
6. What happens during a WebSocket handshake?
7. What is the difference between `ws://` and `wss://`?
8. What are ping, pong, and close frames?

## 2. WebSocket vs Socket.IO

9. What is Socket.IO, and why is it used?
10. What is the difference between native WebSockets and Socket.IO?
11. Is Socket.IO the same as WebSockets?
12. How does Socket.IO establish and maintain a connection?
13. What is transport fallback in Socket.IO?
14. How does automatic reconnection work in Socket.IO?

## 3. Socket.IO Events and Communication

15. What is the difference between `socket.emit()` and `socket.on()`?
16. What is the difference between `io.emit()`, `socket.emit()`, and `socket.broadcast.emit()`?
17. What is the difference between `socket.to(room).emit()` and `io.to(room).emit()`?
18. What are Socket.IO rooms, and how do they work?
19. What is the difference between rooms and namespaces?
20. How do you send a message to a specific connected client?
21. How do you handle connection and disconnection events?
22. How do you implement acknowledgements in Socket.IO?

## 4. Group Chat Project Questions

23. Explain the architecture of your real-time group chat application.
24. Explain the complete flow of a message from the sender to the receiver.
25. How does the backend broadcast a message to all users in a chat room?
26. How would you implement joining and leaving chat rooms?
27. How would you identify a user and associate them with their socket connection?
28. How would you implement online/offline user status?
29. How would you implement a typing indicator?
30. How would you implement private messaging between two users?
31. How would you display message timestamps and sender information?
32. How would you handle a user opening the application in multiple tabs?
33. How would you implement message delivery and read receipts?
34. What are the limitations of your current group chat implementation?

## 5. Message Delivery and Reliability

35. Does WebSocket guarantee that every message will be delivered?
36. What is the difference between at-most-once and at-least-once delivery?
37. How do you prevent duplicate messages?
38. What happens if a user disconnects while a message is being sent?
39. How do you persist chat messages in MongoDB?
40. How would you recover messages missed while a user was offline?
41. How do you maintain message ordering?
42. What happens to messages when the server restarts?

## 6. Authentication and Security

43. How do you authenticate a Socket.IO connection using JWT?
44. What is `socket.handshake.auth`, and how is it used?
45. How do you prevent unauthorized users from joining private rooms?
46. Why should the server validate incoming socket events?
47. How do you prevent spam, message flooding, and abuse?
48. What is Cross-Site WebSocket Hijacking, and how can you prevent it?

## 7. Scalability and Performance

49. How would you scale a WebSocket application to handle thousands of concurrent users?
50. What problems arise when running multiple Socket.IO server instances?
51. What is Redis, and why is the Socket.IO Redis adapter useful?
52. What are sticky sessions, and when are they required?
53. How do you handle slow clients and large message payloads?
54. How would you monitor and debug a WebSocket application in production?

## 8. Advanced Scenario-Based Questions

55. A user sends a message, but the receiver does not get it. How would you debug the issue?
56. Users are receiving duplicate messages. What could cause this, and how would you fix it?
57. A user appears online even after closing the browser. How would you fix the presence system?
58. Your application works locally but fails after deployment. What would you investigate?
59. How would you make your chat application reliable when the network disconnects unexpectedly?
60. If you rebuilt your group chat application for production, what improvements would you make and why?
