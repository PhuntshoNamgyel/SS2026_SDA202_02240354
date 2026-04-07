# Practical 3: Class & Object Diagrams

Practical 3 required us to design a Class diagram and an Object diagram for an Automated Grading System. At first I wasn't sure why both were needed since they looked so similar to each other, but working through the scenario slowly made the difference clear.

## What I Understood

The biggest thing I took away was understanding why both diagrams are needed. The Class diagram shows the structure of the whole system, things like how `Lecturer` creates `Assignment` and how `GradingSystem` depends on `Submission` to run tests and check plagiarism. The Object diagram then brought that to life with a real scenario, showing an actual submission from a student with a score, a grade, and feedback already filled in.

## Challenges

The main challenge was getting the relationships right. Choosing between arrow types took longer than expected, and deciding whether certain objects could exist independently made me think more carefully about how the system actually works. Moving to the object diagram also meant unlearning some habits from the class diagram, like dropping multiplicity and replacing types with actual values.

## Takeaway

Designing both diagrams for the same system made me realize that a Class diagram alone is not enough to validate your design. You need the Object diagram to confirm that your structure actually holds up when real data flows through it. If something feels off when filling in the object diagram, it usually means something in the class diagram needs fixing.