% Define the relationships between students, teachers, and subject codes
teaches('Mr. Smith', 'Math101').
teaches('Mrs. Johnson', 'Eng202').
teaches('Dr. Brown', 'Sci303').
teaches('Ms. Davis', 'Hist404').

enrolled('Alice', 'Math101').
enrolled('Alice', 'Sci303').
enrolled('Bob', 'Eng202').
enrolled('Bob', 'Hist404').
enrolled('Charlie', 'Math101').
enrolled('Charlie', 'Eng202').
enrolled('Diana', 'Sci303').
enrolled('Diana', 'Hist404').

% Rule to find which teacher teaches which student for a given subject code
teaches_student(Teacher, Student, SubjectCode) :-
    teaches(Teacher, SubjectCode),
    enrolled(Student, SubjectCode).
