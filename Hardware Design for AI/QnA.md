# Hardware Design for AI — Q&A

---

### Q1) What is the problem saying in plain English?

**You have a neural network with 64 weights. Each weight is a 10-bit integer (values from 0 to 1023).**

**Normal storage:**
```
64 weights × 10 bits = 640 bits = 80 bytes needed
```

**The problem:** You only have **20 bytes (160 bits)** of main memory left. 80 bytes won't fit in 20 bytes.

**So the question is:** How do you squeeze 64 weights into 20 bytes?
