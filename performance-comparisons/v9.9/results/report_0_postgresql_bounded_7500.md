### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 25ms | 23ms | 1049.10
| DraftStore.Delete | avg | 2ms | 16ms | 14ms | 562.65
| PluginStore.List | avg | 3ms | 12ms | 9ms | 314.33
| DraftStore.GetDraftsForUser | avg | 3ms | 8ms | 5ms | 191.19
| TeamStore.AnalyticsTeamCount | avg | 4ms | 11ms | 7ms | 163.56
| UserStore.GetProfilesInChannel | avg | 31ms | 80ms | 49ms | 158.66
| PostStore.GetPostsAfter | avg | 3ms | 5ms | 2ms | 59.30
| UserStore.Count | avg | 14ms | 21ms | 7ms | 49.63
| UserStore.AnalyticsActiveCount | avg | 22ms | 32ms | 10ms | 45.05
| ChannelStore.AnalyticsTypeCount | avg | 13ms | 15ms | 2ms | 15.91
| UserStore.AutocompleteUsersInChannel | avg | 47ms | 51ms | 4ms | 8.55
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 74ms | 76ms | 2ms | 2.70
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Delete | p99 | 5ms | 49ms | 44ms | 888.89
| PostStore.AnalyticsPostCount | p99 | 5ms | 25ms | 20ms | 403.92
| PostStore.GetPostsAfter | p99 | 8ms | 41ms | 33ms | 395.23
| UserStore.GetProfilesInChannel | p99 | 50ms | 246ms | 196ms | 394.45
| JobStore.Get | p99 | 9ms | 36ms | 27ms | 293.48
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 19ms | 14ms | 282.83
| JobStore.Save | p99 | 5ms | 19ms | 14ms | 282.83
| UserStore.Count | p99 | 38ms | 93ms | 55ms | 145.67
| PluginStore.List | p99 | 22ms | 50ms | 28ms | 128.59
| JobStore.GetCountByStatusAndType | p99 | 9ms | 20ms | 11ms | 121.77
| ComplianceStore.MessageExport | p99 | 9ms | 20ms | 11ms | 119.57
| JobStore.GetAllByTypePage | p99 | 10ms | 21ms | 11ms | 113.99
| LinkMetadataStore.Save | p99 | 21ms | 43ms | 22ms | 106.54
| ChannelStore.GetChannelUnread | p99 | 9ms | 19ms | 10ms | 106.38
| TeamStore.AnalyticsTeamCount | p99 | 24ms | 49ms | 25ms | 105.04
| DraftStore.GetDraftsForUser | p99 | 5ms | 10ms | 5ms | 101.01
| PluginStore.Get | p99 | 5ms | 10ms | 5ms | 101.01
| LicenseStore.GetAll | p99 | 5ms | 10ms | 5ms | 101.01
| FileInfoStore.SetContent | p99 | 31ms | 61ms | 30ms | 97.56
| FileInfoStore.GetForPost | p99 | 9ms | 18ms | 9ms | 96.69
| ChannelStore.UpdateSidebarCategories | p99 | 443ms | 870ms | 427ms | 96.49
| UserStore.AnalyticsActiveCount | p99 | 49ms | 96ms | 47ms | 95.67
| ChannelStore.AnalyticsTypeCount | p99 | 25ms | 48ms | 23ms | 92.65
| UserStore.GetMany | p99 | 23ms | 44ms | 21ms | 92.30
| FileInfoStore.AttachToPost | p99 | 25ms | 45ms | 20ms | 80.31
| UserStore.Update | p99 | 42ms | 73ms | 31ms | 73.46
| FileInfoStore.Get | p99 | 11ms | 19ms | 8ms | 71.80
| PostAcknowledgementStore.GetForPost | p99 | 18ms | 30ms | 12ms | 67.98
| UserStore.GetByUsername | p99 | 16ms | 24ms | 8ms | 51.21
| ChannelStore.CreateDirectChannel | p99 | 134ms | 195ms | 61ms | 45.35
| FileInfoStore.Save | p99 | 23ms | 33ms | 10ms | 43.42
| ChannelStore.GetMember | p99 | 25ms | 32ms | 7ms | 28.20
| JobStore.GetNewestJobByStatusesAndType | p99 | 8ms | 10ms | 2ms | 24.24
| EmojiStore.GetByName | p99 | 17ms | 21ms | 4ms | 24.13
| PostStore.Update | p99 | 78ms | 96ms | 18ms | 22.93
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 22ms | 4ms | 21.92
| PostStore.GetSingle | p99 | 14ms | 17ms | 3ms | 21.46
| UserStore.UpdateLastLogin | p99 | 24ms | 29ms | 5ms | 20.50
| ThreadStore.UpdateMembership | p99 | 10ms | 12ms | 2ms | 20.02
| PreferenceStore.GetAll | p99 | 31ms | 37ms | 6ms | 19.09
| LinkMetadataStore.Get | p99 | 16ms | 19ms | 3ms | 18.90
| TeamStore.Get | p99 | 16ms | 19ms | 3ms | 18.89
| ThreadStore.GetThreadForUser | p99 | 28ms | 33ms | 5ms | 17.78
| TeamStore.SaveMember | p99 | 100ms | 116ms | 16ms | 16.05
| ChannelStore.GetFileCount | p99 | 22ms | 25ms | 3ms | 13.69
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 177ms | 199ms | 22ms | 12.46
| StatusStore.GetByIds | p99 | 18ms | 20ms | 2ms | 11.30
| StatusStore.UpdateLastActivityAt | p99 | 18ms | 20ms | 2ms | 11.22
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 18ms | 20ms | 2ms | 11.12
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 38ms | 42ms | 4ms | 10.58
| UserStore.UpdateFailedPasswordAttempts | p99 | 32ms | 35ms | 3ms | 9.29
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 24ms | 26ms | 2ms | 8.42
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 25ms | 27ms | 2ms | 8.08
| ChannelStore.GetGuestCount | p99 | 37ms | 40ms | 3ms | 8.02
| UserTermsOfServiceStore.GetByUser | p99 | 25ms | 27ms | 2ms | 7.94
| PluginStore.SetWithOptions | p99 | 38ms | 41ms | 3ms | 7.82
| TeamStore.GetTeamsForUser | p99 | 29ms | 31ms | 2ms | 7.00
| UserStore.GetForLogin | p99 | 33ms | 35ms | 2ms | 6.14
| PostStore.Save | p99 | 67ms | 71ms | 4ms | 6.01
| ThreadStore.GetTeamsUnreadForUser | p99 | 35ms | 37ms | 2ms | 5.69
| PreferenceStore.Save | p99 | 81ms | 84ms | 3ms | 3.70
| SessionStore.Get | p99 | 61ms | 63ms | 2ms | 3.28
| ChannelStore.SaveMember | p99 | 195ms | 201ms | 6ms | 3.08
| ProductNoticesStore.View | p99 | 236ms | 243ms | 7ms | 2.97
| UserStore.Save | p99 | 220ms | 224ms | 4ms | 1.81
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.PermanentDeleteByName | avg | 3ms | 0s | -3ms | -106.54
| SystemStore.SaveOrUpdate | avg | 7ms | 0s | -7ms | -104.63
| UserStore.GetUserCountForReport | avg | 9ms | 0s | -9ms | -103.47
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -97.89
| RetentionPolicyStore.GetAll | avg | 40ms | 3ms | -37ms | -91.92
| StatusStore.SaveOrUpdate | avg | 76ms | 18ms | -58ms | -76.36
| RetentionPolicyStore.GetCount | avg | 13ms | 4ms | -9ms | -70.43
| ChannelStore.SearchGroupChannels | avg | 13ms | 5ms | -8ms | -60.26
| ChannelStore.GetSidebarCategory | avg | 24ms | 11ms | -13ms | -53.38
| ChannelStore.AutocompleteInTeamForSearch | avg | 54ms | 26ms | -28ms | -52.20
| RoleStore.ChannelHigherScopedPermissions | avg | 10ms | 5ms | -5ms | -50.34
| StatusStore.UpdateExpiredDNDStatuses | avg | 4ms | 2ms | -2ms | -49.05
| ChannelStore.CreateInitialSidebarCategories | avg | 46ms | 24ms | -22ms | -48.22
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 36ms | 20ms | -16ms | -45.07
| TeamStore.GetTotalMemberCount | avg | 46ms | 30ms | -16ms | -34.72
| PostStore.GetPostReminders | avg | 7ms | 5ms | -2ms | -29.22
| ChannelStore.GetTeamChannels | avg | 27ms | 20ms | -7ms | -25.75
| ChannelStore.Save | avg | 17ms | 14ms | -3ms | -18.10
| ChannelStore.UpdateSidebarCategories | avg | 88ms | 73ms | -15ms | -17.01
| PostStore.SearchPostsForUser | avg | 182ms | 157ms | -25ms | -13.74
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 10ms | 0s | -10ms | -100.50
| UserStore.GetUserCountForReport | p99 | 10ms | 0s | -10ms | -100.50
| RetentionPolicyStore.GetAll | p99 | 50ms | 5ms | -45ms | -90.45
| ThreadStore.Get | p99 | 64ms | 6ms | -58ms | -89.93
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 9ms | -37ms | -80.87
| ChannelStore.GetSidebarCategory | p99 | 193ms | 39ms | -154ms | -79.78
| PostPersistentNotificationStore.DeleteExpired | p99 | 43ms | 9ms | -34ms | -79.07
| SessionStore.Remove | p99 | 24ms | 9ms | -15ms | -63.83
| PostStore.GetPostReminders | p99 | 24ms | 10ms | -14ms | -59.01
| UserStore.GetProfilesNotInChannel | p99 | 24ms | 10ms | -14ms | -58.45
| RoleStore.ChannelHigherScopedPermissions | p99 | 91ms | 39ms | -52ms | -57.46
| StatusStore.SaveOrUpdate | p99 | 901ms | 388ms | -513ms | -56.97
| ChannelStore.Save | p99 | 205ms | 88ms | -117ms | -56.94
| TeamStore.GetTotalMemberCount | p99 | 99ms | 50ms | -49ms | -49.58
| ChannelStore.GetTeamChannels | p99 | 96ms | 49ms | -47ms | -48.71
| UserAccessTokenStore.GetByToken | p99 | 43ms | 23ms | -20ms | -47.06
| JobStore.UpdateOptimistically | p99 | 16ms | 9ms | -7ms | -44.59
| ChannelStore.SearchGroupChannels | p99 | 40ms | 25ms | -15ms | -37.32
| ChannelStore.GetAllChannelMembersForUser | p99 | 37ms | 26ms | -11ms | -30.02
| ChannelStore.Autocomplete | p99 | 138ms | 100ms | -38ms | -27.51
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 122ms | 91ms | -31ms | -25.36
| ClusterDiscoveryStore.SetLastPingAt | p99 | 31ms | 24ms | -7ms | -22.95
| ChannelStore.AutocompleteInTeamForSearch | p99 | 208ms | 168ms | -40ms | -19.23
| StatusStore.Get | p99 | 29ms | 25ms | -4ms | -13.76
| ReactionStore.GetForPost | p99 | 23ms | 20ms | -3ms | -13.25
| ChannelStore.CreateInitialSidebarCategories | p99 | 199ms | 173ms | -26ms | -13.03
| PostPriorityStore.GetForPost | p99 | 25ms | 22ms | -3ms | -11.77
| ThreadStore.GetTotalThreads | p99 | 28ms | 25ms | -3ms | -10.88
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 28ms | 25ms | -3ms | -10.81
| JobStore.GetAllByStatus | p99 | 36ms | 33ms | -3ms | -8.44
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 201ms | 186ms | -15ms | -7.47
| ThreadStore.GetTotalUnreadMentions | p99 | 27ms | 25ms | -2ms | -7.27
| UserStore.AutocompleteUsersInChannel | p99 | 303ms | 295ms | -8ms | -2.64
| PostStore.SearchPostsForUser | p99 | 2.34s | 2.315s | -25ms | -1.07
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 1ms | 7ms | 6ms | 818.37
| getAnalytics | avg | 27ms | 66ms | 39ms | 143.88
| getPrevTrialLicense | avg | 1ms | 3ms | 2ms | 141.05
| createPost | avg | 334ms | 355ms | 21ms | 6.28
| autocompleteUsers | avg | 41ms | 43ms | 2ms | 4.89
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getAnalytics | p99 | 50ms | 475ms | 425ms | 858.07
| getRolesByNames | p99 | 10ms | 24ms | 14ms | 146.60
| getJobsByType | p99 | 10ms | 21ms | 11ms | 113.99
| getPrevTrialLicense | p99 | 5ms | 10ms | 5ms | 101.01
| setPostReminder | p99 | 25ms | 49ms | 24ms | 96.55
| getChannelUnread | p99 | 10ms | 19ms | 9ms | 92.07
| updateCategoriesForTeamForUser | p99 | 471ms | 870ms | 399ms | 84.67
| root | p99 | 5ms | 8ms | 3ms | 60.61
| saveReaction | p99 | 50ms | 72ms | 22ms | 44.10
| updatePreferences | p99 | 29ms | 39ms | 10ms | 34.72
| getPreferences | p99 | 33ms | 39ms | 6ms | 18.04
| getUsers | p99 | 46ms | 54ms | 8ms | 17.22
| getChannel | p99 | 38ms | 43ms | 5ms | 13.07
| getChannelMembersForTeamForUser | p99 | 27ms | 30ms | 3ms | 11.14
| viewChannel | p99 | 71ms | 77ms | 6ms | 8.44
| getClientConfig | p99 | 75ms | 81ms | 6ms | 8.04
| getPostThread | p99 | 70ms | 75ms | 5ms | 7.11
| getAllTeams | p99 | 38ms | 40ms | 2ms | 5.29
| createPost | p99 | 1.716s | 1.8s | 84ms | 4.89
| getPostsForChannelAroundLastUnread | p99 | 188ms | 196ms | 8ms | 4.25
| autocompleteUsers | p99 | 202ms | 210ms | 8ms | 3.97
| createUser | p99 | 484ms | 491ms | 7ms | 1.45
| login | p99 | 448ms | 454ms | 6ms | 1.34
| getPostsForChannel | p99 | 224ms | 227ms | 3ms | 1.34
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroupsAssociatedToChannelsByTeam | avg | 3ms | 0s | -3ms | -119.01
| getDrafts | avg | 3ms | 0s | -3ms | -114.28
| getTotalUsersStats | avg | 12ms | 0s | -12ms | -103.19
| getChannelMembersForUser | avg | 11ms | 0s | -11ms | -102.53
| getLicenseSelfServeStatus | avg | 76ms | 0s | -76ms | -100.26
| getGroups | avg | 2ms | 0s | -2ms | -80.68
| getProductNotices | avg | 2ms | 0s | -2ms | -80.36
| upsertDraft | avg | 7ms | 3ms | -4ms | -61.12
| searchGroupChannels | avg | 13ms | 5ms | -8ms | -59.99
| autocompleteChannelsForTeamForSearch | avg | 54ms | 26ms | -28ms | -52.14
| followThreadByUser | avg | 28ms | 14ms | -14ms | -50.87
| getCategoriesForTeamForUser | avg | 36ms | 20ms | -16ms | -44.73
| updateCategoriesForTeamForUser | avg | 134ms | 98ms | -36ms | -26.85
| createChannel | avg | 304ms | 250ms | -54ms | -17.74
| searchPostsInTeam | avg | 192ms | 166ms | -26ms | -13.56
| logout | avg | 60ms | 53ms | -7ms | -11.73
| createGroupChannel | avg | 401ms | 361ms | -40ms | -9.97
| removeUserCustomStatus | avg | 169ms | 160ms | -9ms | -5.33
| getTeamStats | avg | 57ms | 54ms | -3ms | -5.26
| getProfileImage | avg | 85ms | 82ms | -3ms | -3.53
| createDirectChannel | avg | 248ms | 241ms | -7ms | -2.82
| addTeamMember | avg | 891ms | 869ms | -22ms | -2.47
| uploadFileStream | avg | 361ms | 356ms | -5ms | -1.39
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembersForUser | p99 | 25ms | 0s | -25ms | -101.21
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -100.97
| getSelfHostedProducts | p99 | 5ms | 0s | -5ms | -100.92
| getTotalUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getLicenseSelfServeStatus | p99 | 100ms | 0s | -100ms | -100.49
| followThreadByUser | p99 | 230ms | 25ms | -205ms | -88.94
| upsertDraft | p99 | 24ms | 5ms | -19ms | -77.87
| logout | p99 | 235ms | 99ms | -136ms | -57.87
| deleteDraft | p99 | 10ms | 5ms | -5ms | -51.02
| searchGroupChannels | p99 | 40ms | 25ms | -15ms | -37.32
| getCategoriesForTeamForUser | p99 | 133ms | 92ms | -41ms | -30.87
| searchAllChannels | p99 | 138ms | 100ms | -38ms | -27.51
| getChannelsForUser | p99 | 46ms | 34ms | -12ms | -26.28
| autocompleteChannelsForTeamForSearch | p99 | 208ms | 168ms | -40ms | -19.23
| patchPost | p99 | 228ms | 191ms | -37ms | -16.21
| getThreadsForUser | p99 | 32ms | 30ms | -2ms | -6.22
| getTeamMembersForUser | p99 | 43ms | 41ms | -2ms | -4.68
| getUser | p99 | 49ms | 47ms | -2ms | -4.06
| updateReadStateThreadByUser | p99 | 189ms | 183ms | -6ms | -3.18
| createGroupChannel | p99 | 971ms | 944ms | -27ms | -2.78
| unfollowThreadByUser | p99 | 166ms | 164ms | -2ms | -1.20
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 33ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.929
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 74ms| 76ms | 2ms | 2.695
| |  P99| 177ms| 199ms | 22ms | 12.465
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.362
| ChannelStore.AnalyticsTypeCount |  Avg| 13ms| 15ms | 2ms | 15.913
| |  P99| 25ms| 48ms | 23ms | 92.648
| ChannelStore.Autocomplete |  Avg| 44ms| 45ms | 1ms | 2.251
| |  P99| 138ms| 100ms | -38ms | -27.507
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 54ms| 26ms | -28ms | -52.196
| |  P99| 208ms| 168ms | -40ms | -19.232
| ChannelStore.CreateDirectChannel |  Avg| 26ms| 25ms | -1ms | -3.782
| |  P99| 134ms| 195ms | 61ms | 45.353
| ChannelStore.CreateInitialSidebarCategories |  Avg| 46ms| 24ms | -22ms | -48.222
| |  P99| 199ms| 173ms | -26ms | -13.034
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 13ms| 14ms | 1ms | 7.836
| |  P99| 38ms| 42ms | 4ms | 10.582
| ChannelStore.GetAllChannelMembersForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 37ms| 26ms | -11ms | -30.017
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 201ms| 186ms | -15ms | -7.473
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 45ms | 1ms | 2.295
| ChannelStore.GetChannelUnread |  Avg| 2ms| 3ms | 1ms | 40.820
| |  P99| 9ms| 19ms | 10ms | 106.384
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 3ms | -1ms | -28.213
| |  P99| 19ms| 20ms | 1ms | 5.141
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.774
| ChannelStore.GetFileCount |  Avg| 3ms| 4ms | 1ms | 29.586
| |  P99| 22ms| 25ms | 3ms | 13.685
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 40ms | 3ms | 8.021
| ChannelStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 32ms | 7ms | 28.200
| ChannelStore.GetMemberCount |  Avg| 23ms| 22ms | -1ms | -4.392
| |  P99| 83ms| 83ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 29ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.047
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 36ms| 20ms | -16ms | -45.065
| |  P99| 122ms| 91ms | -31ms | -25.355
| ChannelStore.GetSidebarCategory |  Avg| 24ms| 11ms | -13ms | -53.380
| |  P99| 193ms| 39ms | -154ms | -79.784
| ChannelStore.GetTeamChannels |  Avg| 27ms| 20ms | -7ms | -25.747
| |  P99| 96ms| 49ms | -47ms | -48.705
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.367
| ChannelStore.Save |  Avg| 17ms| 14ms | -3ms | -18.103
| |  P99| 205ms| 88ms | -117ms | -56.937
| ChannelStore.SaveMember |  Avg| 36ms| 37ms | 1ms | 2.740
| |  P99| 195ms| 201ms | 6ms | 3.078
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 5ms | -8ms | -60.265
| |  P99| 40ms| 25ms | -15ms | -37.318
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 88ms| 73ms | -15ms | -17.009
| |  P99| 443ms| 870ms | 427ms | 96.493
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 24ms | -7ms | -22.950
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 119.565
| DraftStore.Delete |  Avg| 2ms| 16ms | 14ms | 562.653
| |  P99| 5ms| 49ms | 44ms | 888.889
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 8ms | 5ms | 191.186
| |  P99| 5ms| 10ms | 5ms | 101.010
| EmojiStore.GetByName |  Avg| 2ms| 3ms | 1ms | 43.037
| |  P99| 17ms| 21ms | 4ms | 24.129
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 45ms | 20ms | 80.309
| FileInfoStore.Get |  Avg| 2ms| 3ms | 1ms | 42.830
| |  P99| 11ms| 19ms | 8ms | 71.795
| FileInfoStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 42.796
| |  P99| 9ms| 18ms | 9ms | 96.690
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 33ms | 10ms | 43.415
| FileInfoStore.SetContent |  Avg| 8ms| 9ms | 1ms | 12.411
| |  P99| 31ms| 61ms | 30ms | 97.562
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.424
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 29ms | -1ms | -3.371
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 36ms | 27ms | 293.478
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 33ms | -3ms | -8.438
| JobStore.GetAllByTypePage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 113.991
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 121.771
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.242
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 30.053
| |  P99| 5ms| 19ms | 14ms | 282.828
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -44.586
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.268
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 21.918
| LicenseStore.GetAll |  Avg| 1ms| 2ms | 1ms | 93.215
| |  P99| 5ms| 10ms | 5ms | 101.010
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.896
| LinkMetadataStore.Save |  Avg| 4ms| 5ms | 1ms | 23.052
| |  P99| 21ms| 43ms | 22ms | 106.542
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.713
| PluginStore.Get |  Avg| 2ms| 3ms | 1ms | 51.289
| |  P99| 5ms| 10ms | 5ms | 101.010
| PluginStore.List |  Avg| 3ms| 12ms | 9ms | 314.328
| |  P99| 22ms| 50ms | 28ms | 128.588
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.818
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 30ms | 12ms | 67.981
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.091
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 2ms | -1ms | -32.992
| |  P99| 43ms| 9ms | -34ms | -79.070
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.788
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -11.769
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 2ms| 25ms | 23ms | 1049.100
| |  P99| 5ms| 25ms | 20ms | 403.923
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.535
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 30ms | 1ms | 3.499
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.088
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 5ms | -2ms | -29.220
| |  P99| 24ms| 10ms | -14ms | -59.009
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 32ms | -1ms | -3.077
| PostStore.GetPostsAfter |  Avg| 3ms| 5ms | 2ms | 59.302
| |  P99| 8ms| 41ms | 33ms | 395.229
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.096
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 74ms| 74ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 3ms | 1ms | 40.081
| |  P99| 14ms| 17ms | 3ms | 21.464
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 67ms| 71ms | 4ms | 6.012
| PostStore.SearchPostsForUser |  Avg| 182ms| 157ms | -25ms | -13.743
| |  P99| 2.34s| 2.315s | -25ms | -1.068
| PostStore.SetPostReminder |  Avg| 7ms| 6ms | -1ms | -14.873
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 78ms| 96ms | 18ms | 22.931
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.327
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 37ms | 6ms | 19.089
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 81ms| 84ms | 3ms | 3.702
| ProductNoticesStore.GetViews |  Avg| 2ms| 3ms | 1ms | 42.123
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 41ms| 41ms | 0s | 0.000
| |  P99| 236ms| 243ms | 7ms | 2.966
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.253
| RetentionPolicyStore.GetAll |  Avg| 40ms| 3ms | -37ms | -91.923
| |  P99| 50ms| 5ms | -45ms | -90.452
| RetentionPolicyStore.GetCount |  Avg| 13ms| 4ms | -9ms | -70.434
| |  P99| 25ms| 25ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 10ms| 5ms | -5ms | -50.345
| |  P99| 91ms| 39ms | -52ms | -57.455
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -97.888
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 61ms| 63ms | 2ms | 3.278
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 3ms | 1ms | 43.400
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.123
| SessionStore.Remove |  Avg| 4ms| 3ms | -1ms | -22.488
| |  P99| 24ms| 9ms | -15ms | -63.829
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.143
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.170
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.765
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.301
| StatusStore.SaveOrUpdate |  Avg| 76ms| 18ms | -58ms | -76.356
| |  P99| 901ms| 388ms | -513ms | -56.968
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 2ms | -2ms | -49.054
| |  P99| 46ms| 9ms | -37ms | -80.874
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.223
| SystemStore.GetByName |  Avg| 2ms| 3ms | 1ms | 40.189
| |  P99| 24ms| 25ms | 1ms | 4.128
| SystemStore.PermanentDeleteByName |  Avg| 3ms| 0s | -3ms | -106.542
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 7ms| 0s | -7ms | -104.626
| |  P99| 10ms| 0s | -10ms | -100.503
| TeamStore.AnalyticsTeamCount |  Avg| 4ms| 11ms | 7ms | 163.562
| |  P99| 24ms| 49ms | 25ms | 105.042
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.892
| TeamStore.GetActiveMemberCount |  Avg| 54ms| 54ms | 0s | 0.000
| |  P99| 99ms| 100ms | 1ms | 1.009
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 32ms | 1ms | 3.270
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.077
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.534
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 6.996
| TeamStore.GetTotalMemberCount |  Avg| 46ms| 30ms | -16ms | -34.725
| |  P99| 99ms| 50ms | -49ms | -49.578
| TeamStore.SaveMember |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 100ms| 116ms | 16ms | 16.047
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -33.616
| |  P99| 64ms| 6ms | -58ms | -89.933
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 37ms | 2ms | 5.689
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 28ms| 33ms | 5ms | 17.780
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.078
| ThreadStore.GetTotalThreads |  Avg| 4ms| 3ms | -1ms | -28.223
| |  P99| 28ms| 25ms | -3ms | -10.884
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 3ms | -1ms | -28.324
| |  P99| 27ms| 25ms | -2ms | -7.273
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 3ms | -1ms | -27.816
| |  P99| 26ms| 25ms | -1ms | -3.814
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.806
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 33ms| 33ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 3ms | -1ms | -27.428
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.021
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 5ms| 4ms | -1ms | -18.569
| |  P99| 43ms| 23ms | -20ms | -47.056
| UserStore.AnalyticsActiveCount |  Avg| 22ms| 32ms | 10ms | 45.046
| |  P99| 49ms| 96ms | 47ms | 95.674
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 3ms | 1ms | 44.834
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 47ms| 51ms | 4ms | 8.546
| |  P99| 303ms| 295ms | -8ms | -2.643
| UserStore.Count |  Avg| 14ms| 21ms | 7ms | 49.626
| |  P99| 38ms| 93ms | 55ms | 145.672
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.260
| UserStore.GetAllProfilesInChannel |  Avg| 253ms| 254ms | 1ms | 0.396
| |  P99| 902ms| 911ms | 9ms | 0.998
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 24ms | 8ms | 51.212
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.144
| UserStore.GetMany |  Avg| 4ms| 5ms | 1ms | 23.449
| |  P99| 23ms| 44ms | 21ms | 92.304
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.162
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.528
| UserStore.GetProfilesInChannel |  Avg| 31ms| 80ms | 49ms | 158.658
| |  P99| 50ms| 246ms | 196ms | 394.446
| UserStore.GetProfilesNotInChannel |  Avg| 6ms| 5ms | -1ms | -16.143
| |  P99| 24ms| 10ms | -14ms | -58.454
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetUserCountForReport |  Avg| 9ms| 0s | -9ms | -103.467
| |  P99| 10ms| 0s | -10ms | -100.503
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.Save |  Avg| 73ms| 73ms | 0s | 0.000
| |  P99| 220ms| 224ms | 4ms | 1.815
| UserStore.Search |  Avg| 37ms| 37ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 42ms| 73ms | 31ms | 73.457
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 32ms| 35ms | 3ms | 9.288
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 29ms | 5ms | 20.498
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 7.943
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.417
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 240ms| 240ms | 0s | 0.000
| | P99| 498ms| 497ms | -1ms | -0.201
| addTeamMember | Avg| 891ms| 869ms | -22ms | -2.468
| | P99| 2.46s| 2.463s | 3ms | 0.122
| autocompleteChannelsForTeamForSearch | Avg| 54ms| 26ms | -28ms | -52.143
| | P99| 208ms| 168ms | -40ms | -19.232
| autocompleteUsers | Avg| 41ms| 43ms | 2ms | 4.891
| | P99| 202ms| 210ms | 8ms | 3.968
| createChannel | Avg| 304ms| 250ms | -54ms | -17.740
| | P99| 497ms| 493ms | -4ms | -0.806
| createDirectChannel | Avg| 248ms| 241ms | -7ms | -2.824
| | P99| 499ms| 498ms | -1ms | -0.201
| createGroupChannel | Avg| 401ms| 361ms | -40ms | -9.968
| | P99| 971ms| 944ms | -27ms | -2.779
| createPost | Avg| 334ms| 355ms | 21ms | 6.280
| | P99| 1.716s| 1.8s | 84ms | 4.895
| createUser | Avg| 142ms| 141ms | -1ms | -0.702
| | P99| 484ms| 491ms | 7ms | 1.447
| deleteDraft | Avg| 3ms| 2ms | -1ms | -30.872
| | P99| 10ms| 5ms | -5ms | -51.020
| deletePost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 49ms| 48ms | -1ms | -2.030
| followThreadByUser | Avg| 28ms| 14ms | -14ms | -50.871
| | P99| 230ms| 25ms | -205ms | -88.939
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 40ms | 2ms | 5.292
| getAnalytics | Avg| 27ms| 66ms | 39ms | 143.881
| | P99| 50ms| 475ms | 425ms | 858.074
| getCategoriesForTeamForUser | Avg| 36ms| 20ms | -16ms | -44.725
| | P99| 133ms| 92ms | -41ms | -30.867
| getChannel | Avg| 6ms| 7ms | 1ms | 15.454
| | P99| 38ms| 43ms | 5ms | 13.071
| getChannelMember | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 82ms| 82ms | 0s | 0.000
| getChannelMembers | Avg| 4ms| 5ms | 1ms | 24.837
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 4ms| 5ms | 1ms | 22.256
| | P99| 27ms| 30ms | 3ms | 11.139
| getChannelMembersForUser | Avg| 11ms| 0s | -11ms | -102.534
| | P99| 25ms| 0s | -25ms | -101.214
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.067
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 19ms | 9ms | 92.072
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 32ms| 32ms | 0s | 0.000
| getChannelsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 46ms| 34ms | -12ms | -26.278
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 75ms| 81ms | 6ms | 8.043
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 0s | -3ms | -114.285
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 94ms| 95ms | 1ms | 1.065
| getFilteredUsersStats | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 0s | -2ms | -80.678
| | P99| 5ms| 0s | -5ms | -101.010
| getGroupsAssociatedToChannelsByTeam | Avg| 3ms| 0s | -3ms | -119.006
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 21ms | 11ms | 113.991
| getLicenseSelfServeStatus | Avg| 76ms| 0s | -76ms | -100.258
| | P99| 100ms| 0s | -100ms | -100.485
| getPostThread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 70ms| 75ms | 5ms | 7.108
| getPostsForChannel | Avg| 27ms| 28ms | 1ms | 3.657
| | P99| 224ms| 227ms | 3ms | 1.338
| getPostsForChannelAroundLastUnread | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 188ms| 196ms | 8ms | 4.252
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 33ms| 39ms | 6ms | 18.042
| getPrevTrialLicense | Avg| 1ms| 3ms | 2ms | 141.055
| | P99| 5ms| 10ms | 5ms | 101.010
| getProductNotices | Avg| 2ms| 0s | -2ms | -80.364
| | P99| 5ms| 0s | -5ms | -100.967
| getProfileImage | Avg| 85ms| 82ms | -3ms | -3.529
| | P99| 415ms| 416ms | 1ms | 0.241
| getPublicChannelsForTeam | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 7ms | 6ms | 818.369
| | P99| 10ms| 24ms | 14ms | 146.599
| getSelfHostedProducts | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.924
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.680
| getTeamStats | Avg| 57ms| 54ms | -3ms | -5.261
| | P99| 99ms| 100ms | 1ms | 1.007
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 30ms | -1ms | -3.246
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 32ms| 30ms | -2ms | -6.224
| getTotalUsersStats | Avg| 12ms| 0s | -12ms | -103.194
| | P99| 25ms| 0s | -25ms | -100.604
| getUser | Avg| 5ms| 4ms | -1ms | -21.579
| | P99| 49ms| 47ms | -2ms | -4.065
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 46ms| 54ms | 8ms | 17.223
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.475
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 78ms| 77ms | -1ms | -1.286
| | P99| 448ms| 454ms | 6ms | 1.341
| logout | Avg| 60ms| 53ms | -7ms | -11.731
| | P99| 235ms| 99ms | -136ms | -57.871
| patchPost | Avg| 32ms| 33ms | 1ms | 3.126
| | P99| 228ms| 191ms | -37ms | -16.211
| removeUserCustomStatus | Avg| 169ms| 160ms | -9ms | -5.331
| | P99| 480ms| 478ms | -2ms | -0.416
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.606
| saveReaction | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 50ms| 72ms | 22ms | 44.096
| searchAllChannels | Avg| 45ms| 46ms | 1ms | 2.238
| | P99| 138ms| 100ms | -38ms | -27.507
| searchGroupChannels | Avg| 13ms| 5ms | -8ms | -59.989
| | P99| 40ms| 25ms | -15ms | -37.318
| searchPostsInTeam | Avg| 192ms| 166ms | -26ms | -13.558
| | P99| 2.36s| 2.342s | -18ms | -0.763
| searchUsers | Avg| 38ms| 39ms | 1ms | 2.605
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 25ms| 49ms | 24ms | 96.545
| unfollowThreadByUser | Avg| 16ms| 17ms | 1ms | 6.336
| | P99| 166ms| 164ms | -2ms | -1.205
| updateCategoriesForTeamForUser | Avg| 134ms| 98ms | -36ms | -26.852
| | P99| 471ms| 870ms | 399ms | 84.668
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 29ms| 39ms | 10ms | 34.721
| updateReadStateAllThreadsByUser | Avg| 4ms| 3ms | -1ms | -26.869
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 189ms| 183ms | -6ms | -3.177
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 361ms| 356ms | -5ms | -1.387
| | P99| 988ms| 983ms | -5ms | -0.506
| upsertDraft | Avg| 7ms| 3ms | -4ms | -61.116
| | P99| 24ms| 5ms | -19ms | -77.866
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 71ms| 77ms | 6ms | 8.438
