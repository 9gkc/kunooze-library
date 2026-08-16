# CyKun Reader 1.0.1+13

This maintenance release fixes an empty Reader catalog caused by missing `academicYears` parent documents in the production Firestore hierarchy. The Reader now remains resilient when published semesters and subjects exist while the parent collection is temporarily absent.

It also keeps the corrected shield launcher icon sizing and contains no Publisher source, Firebase configuration, signing material, or secrets.
