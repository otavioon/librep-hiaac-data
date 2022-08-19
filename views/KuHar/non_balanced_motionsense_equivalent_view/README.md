# Non-Balanced MotionSense equivalent KuHar Dataset View

This view contains train, validation and test subsets in the following proportions:
- Train: 70% of samples
- Validation: 10% of samples
- Test: 20% of samples

## Activities:

This view contains only samples with activities codes equivalent to MotionSense.
In this way, only activities: Stair-down, Stair-up, Sit, Stand, Walk, Run, were selected.
To each activity were assigned the same MotionSense activity code, thus: 16 (Stair-down in KuHar) became 0 (in MotionSense), 15 (Stair-up in KuHar) became 1 (in MotionSense), 1 (Sit in KuHar) became 2 (in MotionSense), 0 (Stand in KuHar) became 3 (in MotionSense), 11 (Walk in KuHar) became 4 (in MotionSense), 14 (Run in KuHar) became 5 (in MotionSense)

- 0: Stair-down (242 train, 13 validation, 538 test)
- 1: Stair-up (254 train, 18 validation, 542 test)
- 2: Sit (1273 train, 160 validation, 379 test)
- 3: Stand (1273 train, 160 validation, 397 test)
- 4: Walk (630 train, 57 validation, 104 test)
- 5: Run (231 train, 10 validation, 319 test)

## Users
- 56 users train dataset: 1001 (42 samples), 1002 (164 samples), 1003 (43 samples), 1004 (94 samples), 1006 (41 samples), 1007 (40 samples), 1011 (40 samples), 1013 (77 samples), 1014 (148 samples), 1015 (79 samples), 1016 (42 samples), 1017 (40 samples), 1018 (40 samples), 1019 (40 samples), 1021 (42 samples), 1022 (145 samples), 1023 (102 samples), 1024 (172 samples), 1026 (152 samples), 1027 (99 samples), 1028 (40 samples), 1029 (40 samples), 1030 (41 samples), 1032 (40 samples), 1035 (22 samples), 1036 (94 samples), 1037 (110 samples), 1038 (85 samples), 1039 (187 samples), 1040 (142 samples), 1042 (163 samples), 1044 (158 samples), 1045 (101 samples), 1046 (115 samples), 1047 (49 samples), 1048 (46 samples), 1049 (51 samples), 1050 (45 samples), 1053 (40 samples), 1054 (40 samples), 1055 (40 samples), 1057 (45 samples), 1058 (40 samples), 1061 (48 samples), 1062 (41 samples), 1064 (44 samples), 1066 (38 samples), 1067 (41 samples), 1068 (58 samples), 1074 (43 samples), 1075 (41 samples), 1076 (41 samples), 1077 (41 samples), 1078 (40 samples), 1080 (26 samples), 1081 (25 samples).
- 7 users validation dataset: 1005 (39 samples), 1031 (63 samples), 1033 (40 samples), 1041 (146 samples), 1051 (50 samples), 1069 (40 samples), 1073 (40 samples).
- 17 users test dataset: 1008 (80 samples), 1009 (40 samples), 1010 (39 samples), 1020 (42 samples), 1025 (39 samples), 1034 (182 samples), 1043 (152 samples), 1052 (52 samples), 1056 (40 samples), 1060 (39 samples), 1063 (78 samples), 1065 (39 samples), 1070 (40 samples), 1071 (58 samples), 1072 (39 samples), 1079 (41 samples), 1101 (1279 samples).

**NOTE**: Each subset contain samples from distinct users, that is, samples of one user belongs exclusivelly to one of three subsets.

