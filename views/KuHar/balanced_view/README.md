# Balanced KuHar View

This view contains train, validation and test subsets in the following proportions:
- Train: 70% of samples
- Validation: 10% of samples
- Test: 20% of samples

After splits, the datasets were balanced in relation to the activity code column, that is, each subset have the same number of activitiy samples.

## Activities:
- 0: Stand (176 train, 13 validation, 24 test)
- 1: Sit (176 train, 13 validation, 24 test)
- 2: Talk-sit (176 train, 13 validation, 24 test)
- 3: Talk-stand (176 train, 13 validation, 24 test)
- 4: Stand-sit (176 train, 13 validation, 24 test)
- 5: Lay (176 train, 13 validation, 24 test)
- 6: Lay-stand (176 train, 13 validation, 24 test)
- 7: Pick (176 train, 13 validation, 24 test)
- 8: Jump (176 train, 13 validation, 24 test)
- 9: Push-up (176 train, 13 validation, 24 test)
- 10: Sit-up (176 train, 13 validation, 24 test)
- 11: Walk (176 train, 13 validation, 24 test)
- 12: Walk-backwards (176 train, 13 validation, 24 test)
- 13: Walk-circle (176 train, 13 validation, 24 test)
- 14: Run (176 train, 13 validation, 24 test)
- 15: Stair-up (176 train, 13 validation, 24 test)
- 16: Stair-down (176 train, 13 validation, 24 test)
- 17: Table-tennis (176 train, 13 validation, 24 test)

## Users
- 62 users train dataset: 1002 (86 samples), 1005 (33 samples), 1006 (21 samples), 1007 (29 samples), 1008 (56 samples), 1010 (12 samples), 1013 (48 samples), 1014 (117 samples), 1015 (72 samples), 1016 (26 samples), 1017 (21 samples), 1019 (27 samples), 1020 (25 samples), 1021 (31 samples), 1022 (89 samples), 1024 (103 samples), 1025 (27 samples), 1026 (87 samples), 1027 (54 samples), 1028 (21 samples), 1030 (36 samples), 1031 (46 samples), 1032 (21 samples), 1033 (16 samples), 1034 (120 samples), 1037 (55 samples), 1038 (58 samples), 1039 (105 samples), 1040 (73 samples), 1041 (87 samples), 1042 (81 samples), 1043 (81 samples), 1044 (94 samples), 1045 (59 samples), 1047 (32 samples), 1048 (32 samples), 1049 (31 samples), 1053 (19 samples), 1054 (9 samples), 1055 (29 samples), 1056 (17 samples), 1058 (27 samples), 1060 (30 samples), 1063 (30 samples), 1066 (19 samples), 1067 (15 samples), 1068 (38 samples), 1070 (26 samples), 1071 (41 samples), 1073 (8 samples), 1075 (11 samples), 1076 (29 samples), 1077 (32 samples), 1078 (16 samples), 1079 (15 samples), 1082 (123 samples), 1083 (30 samples), 1084 (28 samples), 1086 (36 samples), 1087 (24 samples), 1088 (30 samples), 1101 (474 samples).
- 9 users validation dataset: 1009 (15 samples), 1029 (14 samples), 1035 (2 samples), 1036 (53 samples), 1046 (69 samples), 1052 (22 samples), 1061 (34 samples), 1064 (12 samples), 1090 (13 samples).
- 18 users test dataset: 1001 (18 samples), 1003 (26 samples), 1004 (72 samples), 1011 (12 samples), 1018 (21 samples), 1023 (70 samples), 1050 (28 samples), 1051 (21 samples), 1057 (14 samples), 1062 (17 samples), 1065 (17 samples), 1069 (20 samples), 1072 (19 samples), 1074 (15 samples), 1080 (14 samples), 1081 (31 samples), 1085 (6 samples), 1089 (11 samples).

**NOTE**: Each subset contain samples from distinct users, that is, samples of one user belongs exclusivelly to one of three subsets.

