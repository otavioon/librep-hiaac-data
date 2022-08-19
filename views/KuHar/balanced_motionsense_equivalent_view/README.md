# Balanced MotionSense equivalent KuHar Dataset

This view contains train, validation and test subsets in the following proportions:
- Train: 70% of samples
- Validation: 10% of samples
- Test: 20% of samples

After splits, the datasets were balanced in relation to the activity code column, that is, each subset have the same number of activitiy samples.

## Activities:

This view contains only samples with activities codes equivalent to MotionSense.
In this way, only activities: Stair-down, Stair-up, Sit, Stand, Walk, Run, were selected.
To each activity were assigned the same MotionSense activity code, thus: 16 (Stair-down in KuHar) became 0 (in MotionSense), 15 (Stair-up in KuHar) became 1 (in MotionSense), 1 (Sit in KuHar) became 2 (in MotionSense), 0 (Stand in KuHar) became 3 (in MotionSense), 11 (Walk in KuHar) became 4 (in MotionSense), 14 (Run in KuHar) became 5 (in MotionSense)

- 0: Stair-down (231 train, 10 validation, 104 test)
- 1: Stair-up (231 train, 10 validation, 104 test)
- 2: Sit (231 train, 10 validation, 104 test)
- 3: Stand (231 train, 10 validation, 104 test)
- 4: Walk (231 train, 10 validation, 104 test)
- 5: Run (231 train, 10 validation, 104 test)

## Users
- 56 users train dataset: 1001 (8 samples), 1002 (78 samples), 1003 (11 samples), 1004 (57 samples), 1006 (6 samples), 1007 (9 samples), 1011 (12 samples), 1013 (16 samples), 1014 (35 samples), 1015 (14 samples), 1016 (10 samples), 1017 (5 samples), 1018 (5 samples), 1019 (8 samples), 1021 (4 samples), 1022 (33 samples), 1023 (55 samples), 1024 (93 samples), 1026 (57 samples), 1027 (56 samples), 1028 (6 samples), 1029 (9 samples), 1030 (8 samples), 1032 (7 samples), 1035 (7 samples), 1036 (45 samples), 1037 (48 samples), 1038 (32 samples), 1039 (79 samples), 1040 (59 samples), 1042 (97 samples), 1044 (97 samples), 1045 (47 samples), 1046 (61 samples), 1047 (5 samples), 1048 (9 samples), 1049 (15 samples), 1050 (13 samples), 1053 (8 samples), 1054 (5 samples), 1055 (3 samples), 1057 (4 samples), 1058 (12 samples), 1061 (11 samples), 1062 (10 samples), 1064 (7 samples), 1066 (7 samples), 1067 (2 samples), 1068 (13 samples), 1074 (13 samples), 1075 (15 samples), 1076 (6 samples), 1077 (14 samples), 1078 (10 samples), 1080 (16 samples), 1081 (14 samples).
- 7 users validation dataset: 1005 (2 samples), 1031 (6 samples), 1033 (2 samples), 1041 (41 samples), 1051 (4 samples), 1069 (1 samples), 1073 (4 samples).
- 17 users test dataset: 1008 (26 samples), 1009 (12 samples), 1010 (11 samples), 1020 (12 samples), 1025 (7 samples), 1034 (100 samples), 1043 (62 samples), 1052 (23 samples), 1056 (9 samples), 1060 (8 samples), 1063 (17 samples), 1065 (12 samples), 1070 (15 samples), 1071 (15 samples), 1072 (7 samples), 1079 (9 samples), 1101 (279 samples).

**NOTE**: Each subset contain samples from distinct users, that is, samples of one user belongs exclusivelly to one of three subsets.

