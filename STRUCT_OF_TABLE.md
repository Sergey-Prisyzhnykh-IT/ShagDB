﻿Table <SPAN STYLE="COLOR:BLUE">**TAB_HUMAN**</SPAN><span style="margin-left: 10px">(список людей)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span>| идентификатор записи |
| <span style="color:green">**firstname**</span> | имя человека |
| <span style="color:green">**surname**</span> | фамилия человека |
| <span style="color:green">**patronymic**</span> | отчество человека |
| <span style="color:green">**sex**</span> | пол человека |
| <span style="color:green">**age**</span> | возраст человека |

Table <SPAN STYLE="COLOR:BLUE">**TAB_STUDENT**</SPAN><span style="margin-left: 10px">(список студентов)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**human_id**</span> | идентификатор человека |
| <span style="color:green">**status**</span> | статус студента (учится, академ и тд) |

Table <SPAN STYLE="COLOR:BLUE">**TAB_MANAGER**</SPAN><span style="margin-left: 10px">(список менеджеров)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**human_id**</span> | идентификатор человека |
| <span style="color:green">**status**</span> | статус менеджера (работает, в отпуске и тд) |
| <span style="color:green">**salary**</span> | зарплата |

Table <SPAN STYLE="COLOR:BLUE">**TAB_TEACHER**</SPAN><span style="margin-left: 10px">(список преподавателей)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**human_id**</span> | идентификатор человека |
| <span style="color:green">**status**</span> | статус преподавателя (работает, в отпуске и тд) |
| <span style="color:green">**salary**</span> | зарплата |

Table <SPAN STYLE="COLOR:BLUE">**TAB_COURSE**</SPAN><span style="margin-left: 10px">(список факультетов)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**name**</span> | наименование факультета |
| <span style="color:green">**shortname**</span>| сокращённое наименование |

Table <SPAN STYLE="COLOR:BLUE">**TAB_GROUPS**</SPAN><span style="margin-left: 10px">(список всех групп)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**name**</span> | наименование группы |
| <span style="color:green">**course_id**</span> | идентификатор факультета |
| <span style="color:green">**education_form**</span> | форма обучения (стационар, полустационар) |
| <span style="color:green">**start_date**</span> | дата начала обучения |
| <span style="color:green">**finish_date**</span> | дата окончания обучения |
| <span style="color:green">**status**</span> | статус группы (идёт набор, идёт обучение и тд) |

Table <SPAN STYLE="COLOR:BLUE">**TAB_GROUP**</SPAN><span style="margin-left: 10px">(список студентов по группам)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**groups_id**</span> | идентификатор группы |
| <span style="color:green">**student_id**</span>| идентификатор студента |

Table <SPAN STYLE="COLOR:BLUE">**TAB_SUBJECT**</SPAN><span style="margin-left: 10px">(список предметов)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**name**</span> | наименование предмета |
| <span style="color:green">**course_id**</span> | идентификатор факультета |

Table <SPAN STYLE="COLOR:BLUE">**TAB_EDUCATION**</SPAN><span style="margin-left: 10px">(список по связке предмет-группа-преподаватель)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**group_id**</span> | идентификатор группы |
| <span style="color:green">**subject_id**</span>| идентификатор предмета |
|<span style="color:green">**teacher_id**</span> | идентификатор преподавателя |

Table <SPAN STYLE="COLOR:BLUE">**TAB_MAIL**</SPAN><span style="margin-left: 10px">(почта человека)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**mail**</span> | название почты |
| <span style="color:green">**human_id**</span>| идентификатор личности |

Table <SPAN STYLE="COLOR:BLUE">**TAB_PHONE**</SPAN><span style="margin-left: 10px">(телефон человека)

|Columns|Значение|
|:-------------:|:---------------:|
| <span style="color:green">**id**</span> | идентификатор записи |
| <span style="color:green">**phone**</span> | номер телефона |
| <span style="color:green">**human_id**</span>| идентификатор личности |


