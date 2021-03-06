C12 Interupts
=================
This chapter presents general concepts about interrupts and specific details for the **Cortex�-M microcontroller**. We will then use periodic interrupts to cause a software task to be executed on a periodic basis. If a GPIO pin is configured as an input, it can also be armed to invoke an interrupt on falling edges, rising edges, or both falling and rising edges. Using interrupts allows the software to  respond quickly to changes in the external environment.

* Lab12: [440Hz TuningFork](https://www.youtube.com/watch?v=EGfbYhuST9k)

Learning Objectives
=================

* Appreciate the need to perform multiple tasks concurrently.
* Understand real-time performance measures such as bandwidth and latency.
* Learn how interrupts can be used to minimize latency.
* Study the basics of interrupt programming: arm, enable, trigger, vector, priority, acknowledge.
* Understand how to use SysTick to create periodic interrupts.
* Use SysTick to create sounds and spin motors.
