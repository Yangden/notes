# standard queue vs FIFO queue
## Consider pressure test of the system
* Produce event -> write Consume event: Read -> Filter out - number of users and one event -> one email sent
* what does queue play in this scenario: event -> send one email  

 ## Trade-off
 * exactly-once vs dulplicate
 * best-effort order vs strict order
 * throughput - real-time streaming system 