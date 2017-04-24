Tables
=======

All tables in database begins with prefix "T\_" except table WELLS. This preffix is main property which helps to distinct table from other database elements. Below is listed database tables with shorst summary of content. Tables structure and data will be discussed in separate document.

- T_Assumptions - assumet wells flowrates for monthly reports;
- T_BDGT - budgeted monthly production volumes in cubic meters and tonnes on a well basis;
- T_Categories - Classification of the well stanby reason;
- T_Companies - Companies list and average relative density on a company basis;
- T_Dates  - Dates row [1998-01-01 - 2017-12-31];
- T_event_types - Events list with attachment to category from T_Categories;
- T_EVENTS - Occurence of the events in a well;
- T_FIELDS - Fields list;
- T_Holidays - List of holidays and weekends during years 2014-2015. Obsolete table (?);
- T_INJ_DLY - Daily water injection data in the wells;
- T_LIQ_LEVEL - List of dynamic and static liquid levels in annulus;
- T_Oil_Plants - List of production plants;
- T_PROD_DLY - daily prtoduction data from the wells;
- T_PROD_MON - Monthly production data from the wells;
- T_PUMP_WORK_DLY - iformation about wells and pumps work and stanby time on a daily basis;
- T_PUMP_WORK_MON - T_PUMP_WORK_DLY agregated to the monthly basis;
- T_Pumps - List of pump types;
- T_Status - List of possible well status;
- T_Stopping_Reasons - reason of well standby;
- T_TEST - barrel test results;
- T_TEST_PLANNED_MON - ??????;
- T_Well_Purpose - List of available well purposes;
- T_Workover_reasons - well intervention reasons;
- T_Workovers - List of performed workovers in all wells;
- WELLS_ - Wells list.
