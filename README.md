departments.html съдържа главните стилове и темплейт на това как си представям ще изглеждат и работят повечето страници с таблица

Изисквания

С братми чата генерирахме едно опростявване на изискванията за да ги следим по-лесно:


A. Authentication & User Management
   
    A1. Roles & Permissions
    
        A1.1 Define roles: Administrator, Teacher, Department Head, Student
        
        A1.2 Configure permissions for each role

    A2. Registration & Login
        A2.1 Registration form

        A2.2 ⧠ Email confirmation flow

        A2.3 ⧠ Login/logout module

B. College Data Management
    
    B1. College

        B1.1 ⧠ CRUD: name and address

    B2. Faculties

        B2.1 ⧠ CRUD on faculties

    B3. Departments

        B3.1 ⧠ CRUD on departments

        B3.2 ⧠ Link department to faculty

        B3.3 ⧠ Assign department head (role change)

C. Teacher Management

    C1. Teacher Profile

        C1.1 ⧠ CRUD on personal data

        C1.2 ⧠ Permissions and roles (department head)

    C2. Qualifications

        C2.1 ⧠ Add/edit subjects they are qualified to teach

D. Student Management
    
    D1. Student Profile

        D1.1 ⧠ CRUD on personal data

        D1.2 ⧠ Major and college enrollment

E. Courses & Curriculum
    
    E1. Courses

        E1.1 ⧠ CRUD on courses

        E1.2 ⧠ Link course to teacher

    E2. Semester Curriculum

        E2.1 ⧠ Create semester program (list of subjects + assigned teachers)

F. Grades & Attendance

    F1. Grades

        F1.1 ⧠ CRUD on grades (only by course teachers)

    F2. Attendance

        F2.1 ⧠ Mark/edit attendance (only by course teachers)

G. Reporting & Statistics
    
    G1. Rector

        G1.1 ⧠ Access all data

        G1.2 ⧠ Statistics: grade distribution by course, teacher, overall

    G2. Administrator

        G2.1 ⧠ Full data and user management

        G2.2 ⧠ Statistics on grades and attendance across all courses

H. Technical & UI Requirements

    H1. Compatibility

        H1.1 ⧠ Support Chrome, Firefox, Internet Explorer

    H2. Design

        H2.1 ⧠ Responsive UI per role

        H2.2 ⧠ Role-based personalized views
