# Functional Requirements

## Overview

The functional requirements define the system behaviors needed to address the identified user problems and support the proposed solution.

## Requirement Groups

### BR_01 — Provide Timely and Reliable Class Availability Information

The system should provide students with clear and up-to-date information about class availability.

- **FR_01** — The system shall display the current number of available seats and the maximum class capacity.
- **FR_02** — The system shall update the class status when the class reaches its maximum capacity and display the status as "Full".

### BR_02 — Reduce Manual Monitoring

The system should reduce the need for students to repeatedly check class availability.

- **FR_04** — The system shall allow students to join a waitlist when a class is full.

### BR_03 — Support Automated Enrollment

The system should support automated processing when seats become available.

- **FR_06** — The system shall display the student's current position in the waitlist.
- **FR_07** — The system shall automatically process enrollment when a seat becomes available according to the defined waitlist order.
- **FR_08** — The system shall notify the student of the enrollment result.

### BR_04 — Reduce Enrollment Risk

The system should allow students to switch classes without unnecessarily losing their existing enrollment.

- **FR_12** — The system shall retain the student's current enrollment until enrollment in the new class is successfully confirmed.
