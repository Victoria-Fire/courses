Создать проект. В нем два maven подмодуля, один -repository, второй - service. Подключить checkstyle, jacoco.

В maven подмодуле repository реализовать маппинг на JPA entity(Hibernate), создать DAO, используя параметризацию класса через Generic. Базу создавать через liquibase. Покрыть тестами используя H2(базу накатывать через Hibernate).

В maven подмодуле service реализовать подключение maven подмодуля repository. Реализовать класс содержащий main. В main методе наполнить базу тестовыми данными через DAO.

Существует перечень Курсов, за каждым из которых закреплен Преподаватель. Студент записывается на один или несколько Курсов, выполняет задания. Преподаватель выставляет оценки за задания Студенту и добавляет отзыв. Администратор управляет Курсами и Преподавателями. (Поля у сущностей добавляйте по необходимости на свой выбор).
__________
Create a project. It has two maven submodules, one - repository, the second - service. Connect checkstyle, jacoco.

In maven repository submodule implement mapping to JPA entity(Hibernate), create DAO using class parameterization via Generic. Base to create through liquibase. Cover with tests using H2 (roll the database through Hibernate).

In the maven service submodule, implement the maven connection of the repository submodule. Implement a class containing main. In the main method, fill the database with test data via DAO.

There is a list of Courses, each of which is assigned to the Teacher. The student enrolls in one or more courses, completes assignments. The teacher assigns grades for assignments to the Student and adds feedback. The Administrator manages Courses and Instructors. (Add fields to entities as needed of your choice).
