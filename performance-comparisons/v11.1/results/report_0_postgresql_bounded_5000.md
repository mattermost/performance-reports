### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 449ms | 447ms | 27987.88
| ChannelStore.AutocompleteInTeamForSearch | avg | 31ms | 50ms | 19ms | 60.57
| PostStore.GetPostReminders | avg | 5ms | 7ms | 2ms | 36.67
| ChannelStore.GetTeamChannels | avg | 10ms | 13ms | 3ms | 31.45
| ChannelStore.UpdateSidebarCategories | avg | 33ms | 37ms | 4ms | 12.18
| TeamStore.GetTotalMemberCount | avg | 31ms | 33ms | 2ms | 6.39
| ProductNoticesStore.View | avg | 43ms | 45ms | 2ms | 4.70
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 498ms | 493ms | 9957.71
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 26ms | 21ms | 420.04
| PostStore.GetPostReminders | p99 | 10ms | 46ms | 36ms | 363.87
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 231ms | 181ms | 363.82
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 22ms | 17ms | 343.43
| ChannelStore.AutocompleteInTeamForSearch | p99 | 39ms | 100ms | 61ms | 156.43
| ChannelStore.GetTeamChannels | p99 | 10ms | 24ms | 14ms | 140.61
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 21ms | 12ms | 137.91
| JobStore.UpdateOptimistically | p99 | 8ms | 18ms | 10ms | 129.87
| JobStore.Save | p99 | 8ms | 18ms | 10ms | 126.58
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 10ms | 5ms | 101.01
| DraftStore.GetDraftsForUser | p99 | 5ms | 10ms | 5ms | 95.69
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 49ms | 94ms | 45ms | 91.97
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 9ms | 4ms | 80.80
| UserStore.GetByUsername | p99 | 10ms | 18ms | 8ms | 77.64
| FileInfoStore.GetByIds | p99 | 5ms | 8ms | 3ms | 60.30
| ChannelStore.Save | p99 | 24ms | 38ms | 14ms | 58.80
| StatusStore.UpdateExpiredDNDStatuses | p99 | 12ms | 18ms | 6ms | 51.50
| ChannelStore.SearchGroupChannels | p99 | 10ms | 14ms | 4ms | 40.02
| ThreadStore.GetMembershipForUser | p99 | 5ms | 7ms | 2ms | 39.06
| JobStore.GetAllByStatus | p99 | 17ms | 22ms | 5ms | 29.14
| StatusStore.SaveOrUpdateMany | p99 | 20ms | 24ms | 4ms | 20.10
| ChannelStore.UpdateLastViewedAt | p99 | 10ms | 12ms | 2ms | 19.38
| GroupStore.GetByName | p99 | 31ms | 37ms | 6ms | 19.14
| UserStore.Save | p99 | 298ms | 355ms | 57ms | 19.11
| ThreadStore.MaintainMembership | p99 | 17ms | 20ms | 3ms | 17.80
| FileInfoStore.Save | p99 | 17ms | 20ms | 3ms | 17.67
| JobStore.GetCountByStatusAndType | p99 | 16ms | 18ms | 2ms | 12.16
| ThreadStore.GetThreadForUser | p99 | 18ms | 20ms | 2ms | 11.07
| StatusStore.Get | p99 | 27ms | 30ms | 3ms | 11.03
| SessionStore.Get | p99 | 55ms | 61ms | 6ms | 10.86
| JobStore.UpdateStatusOptimistically | p99 | 19ms | 21ms | 2ms | 10.78
| ChannelStore.GetMember | p99 | 31ms | 34ms | 3ms | 9.63
| PostPriorityStore.GetForPost | p99 | 21ms | 23ms | 2ms | 9.38
| TeamStore.GetTeamsByUserId | p99 | 33ms | 36ms | 3ms | 9.14
| PostStore.GetPostIdAfterTime | p99 | 24ms | 26ms | 2ms | 8.23
| UserStore.AutocompleteUsersInChannel | p99 | 161ms | 174ms | 13ms | 8.07
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 25ms | 27ms | 2ms | 8.07
| ChannelStore.GetGuestCount | p99 | 38ms | 41ms | 3ms | 7.86
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 29ms | 31ms | 2ms | 6.87
| TeamStore.GetAllPage | p99 | 33ms | 35ms | 2ms | 6.08
| UserStore.GetForLogin | p99 | 33ms | 35ms | 2ms | 6.04
| PropertyFieldStore.SearchPropertyFields | p99 | 34ms | 36ms | 2ms | 5.90
| PreferenceStore.GetAll | p99 | 38ms | 40ms | 2ms | 5.28
| ProductNoticesStore.View | p99 | 236ms | 245ms | 9ms | 3.82
| TeamStore.SaveMember | p99 | 87ms | 90ms | 3ms | 3.45
| PreferenceStore.Save | p99 | 88ms | 90ms | 2ms | 2.26
| ChannelStore.SaveMember | p99 | 194ms | 198ms | 4ms | 2.06
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -131.09
| ProductNoticesStore.GetViews | avg | 2ms | 0s | -2ms | -129.07
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -128.21
| PluginStore.Delete | avg | 2ms | 0s | -2ms | -114.38
| ComplianceStore.MessageExport | avg | 3ms | 0s | -3ms | -111.06
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -109.33
| UserStore.AnalyticsActiveCount | avg | 12ms | 0s | -12ms | -102.36
| ChannelStore.AnalyticsCountAll | avg | 15ms | 0s | -15ms | -102.27
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -97.38
| PluginStore.SetWithOptions | avg | 4ms | 0s | -4ms | -96.42
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 3ms | 0s | -3ms | -93.60
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -92.83
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 0s | -2ms | -85.06
| ChannelBookmarkStore.Save | avg | 10ms | 8ms | -2ms | -19.80
| ChannelStore.CreateDirectChannel | avg | 20ms | 17ms | -3ms | -15.29
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetAllByTypePage | p99 | 7ms | 0s | -7ms | -102.90
| PluginStore.SetWithOptions | p99 | 10ms | 0s | -10ms | -102.56
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -100.99
| ComplianceStore.MessageExport | p99 | 5ms | 0s | -5ms | -100.92
| ChannelStore.AnalyticsCountAll | p99 | 25ms | 0s | -25ms | -100.78
| UserStore.AnalyticsActiveCount | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.CreateDirectChannel | p99 | 111ms | 25ms | -86ms | -77.80
| LinkMetadataStore.Save | p99 | 21ms | 5ms | -16ms | -76.92
| PostAcknowledgementStore.GetForPost | p99 | 31ms | 10ms | -21ms | -66.92
| ReactionStore.GetForPost | p99 | 27ms | 10ms | -17ms | -62.00
| ChannelBookmarkStore.Save | p99 | 25ms | 10ms | -15ms | -60.73
| PostStore.GetPostReminderMetadata | p99 | 10ms | 5ms | -5ms | -51.28
| ScheduledPostStore.CreateScheduledPost | p99 | 9ms | 5ms | -4ms | -45.45
| UserStore.Update | p99 | 38ms | 22ms | -16ms | -41.83
| ChannelStore.GetPublicChannelsForTeam | p99 | 42ms | 25ms | -17ms | -40.37
| JobStore.UpdateStatus | p99 | 8ms | 5ms | -3ms | -38.22
| ChannelStore.GetFileCount | p99 | 16ms | 10ms | -6ms | -37.71
| PropertyValueStore.SearchPropertyValues | p99 | 20ms | 14ms | -6ms | -29.65
| ChannelStore.CreateInitialSidebarCategories | p99 | 129ms | 114ms | -15ms | -11.62
| ChannelStore.GetChannelsByUser | p99 | 35ms | 31ms | -4ms | -11.54
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 28ms | 25ms | -3ms | -10.57
| UserStore.UpdateFailedPasswordAttempts | p99 | 39ms | 36ms | -3ms | -7.67
| SystemStore.GetByName | p99 | 32ms | 30ms | -2ms | -6.23
| ChannelStore.GetMembersForUserWithPagination | p99 | 36ms | 34ms | -2ms | -5.52
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 31ms | 50ms | 19ms | 60.42
| logout | avg | 18ms | 23ms | 5ms | 27.71
| createChannel | avg | 153ms | 179ms | 26ms | 16.94
| deletePost | avg | 18ms | 21ms | 3ms | 16.29
| updateCategoriesForTeamForUser | avg | 48ms | 52ms | 4ms | 8.32
| getTeamStats | avg | 31ms | 33ms | 2ms | 6.35
| removeUserCustomStatus | avg | 106ms | 111ms | 5ms | 4.73
| addChannelMember | avg | 157ms | 164ms | 7ms | 4.46
| getProfileImage | avg | 113ms | 117ms | 4ms | 3.53
| login | avg | 147ms | 152ms | 5ms | 3.41
| createPost | avg | 138ms | 142ms | 4ms | 2.89
| createUser | avg | 216ms | 221ms | 5ms | 2.31
| createGroupChannel | avg | 250ms | 253ms | 3ms | 1.20
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 25ms | 93ms | 68ms | 273.64
| autocompleteChannelsForTeamForSearch | p99 | 42ms | 100ms | 58ms | 138.93
| updateCategoriesForTeamForUser | p99 | 98ms | 231ms | 133ms | 135.71
| createChannel | p99 | 249ms | 490ms | 241ms | 96.98
| getDrafts | p99 | 5ms | 10ms | 5ms | 95.38
| deletePost | p99 | 25ms | 48ms | 23ms | 92.56
| getChannel | p99 | 12ms | 21ms | 9ms | 76.27
| createGroupChannel | p99 | 496ms | 780ms | 284ms | 57.31
| getProfileImage | p99 | 498ms | 770ms | 272ms | 54.59
| addChannelMember | p99 | 250ms | 368ms | 118ms | 47.21
| getTeamMember | p99 | 5ms | 7ms | 2ms | 40.04
| patchPost | p99 | 38ms | 46ms | 8ms | 21.10
| saveReaction | p99 | 29ms | 35ms | 6ms | 20.99
| searchGroupChannels | p99 | 12ms | 14ms | 2ms | 17.19
| getChannelMember | p99 | 67ms | 77ms | 10ms | 14.93
| autocompleteUsers | p99 | 132ms | 149ms | 17ms | 12.92
| getThreadsForUser | p99 | 28ms | 31ms | 3ms | 10.67
| createDirectChannel | p99 | 279ms | 308ms | 29ms | 10.38
| getPostsForChannelAroundLastUnread | p99 | 161ms | 177ms | 16ms | 9.92
| getTeamsForUser | p99 | 33ms | 36ms | 3ms | 8.98
| createUser | p99 | 496ms | 538ms | 42ms | 8.46
| createPost | p99 | 684ms | 739ms | 55ms | 8.04
| viewChannel | p99 | 34ms | 36ms | 2ms | 5.94
| getPreferences | p99 | 39ms | 41ms | 2ms | 5.13
| getTeamScheduledPosts | p99 | 55ms | 57ms | 2ms | 3.64
| login | p99 | 931ms | 961ms | 30ms | 3.22
| searchPostsInTeam | p99 | 916ms | 929ms | 13ms | 1.42
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 2ms | 0s | -2ms | -116.06
| getJobsByType | avg | 2ms | 0s | -2ms | -114.57
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -112.69
| getUsersByGroupChannelIds | avg | 5ms | 0s | -5ms | -110.87
| getUserByUsername | avg | 2ms | 0s | -2ms | -106.89
| getServerLimits | avg | 10ms | 0s | -10ms | -104.42
| getRolesByNames | avg | 2ms | 0s | -2ms | -102.44
| getFilteredUsersStats | avg | 9ms | 0s | -9ms | -100.84
| getAnalytics | avg | 27ms | 0s | -27ms | -100.55
| handleCheckCWSConnection | avg | 68ms | 0s | -68ms | -99.59
| updateReadStateAllThreadsByUser | avg | 4ms | 0s | -4ms | -90.19
| getGroups | avg | 2ms | 0s | -2ms | -87.88
| createChannelBookmark | avg | 14ms | 12ms | -2ms | -14.69
| createDirectChannel | avg | 168ms | 164ms | -4ms | -2.38
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | p99 | 7ms | 0s | -7ms | -102.90
| getUserByUsername | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| getRolesByNames | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 10ms | 0s | -10ms | -100.49
| handleCheckCWSConnection | p99 | 100ms | 0s | -100ms | -100.48
| getAnalytics | p99 | 49ms | 0s | -49ms | -99.12
| getServerLimits | p99 | 24ms | 0s | -24ms | -98.36
| getPublicChannelsForTeam | p99 | 42ms | 25ms | -17ms | -40.37
| uploadFileStream | p99 | 1.59s | 995ms | -595ms | -37.42
| listCPAValues | p99 | 20ms | 14ms | -6ms | -29.65
| getChannelsForUser | p99 | 35ms | 31ms | -4ms | -11.29
| getChannelMembersForUser | p99 | 37ms | 35ms | -2ms | -5.41
| getClientConfig | p99 | 81ms | 77ms | -4ms | -4.96
| getUsers | p99 | 49ms | 47ms | -2ms | -4.06
| getFileThumbnail | p99 | 95ms | 93ms | -2ms | -2.12
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 36ms| 36ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 70.187
| |  P99| 5ms| 22ms | 17ms | 343.434
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -109.331
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 10ms| 8ms | -2ms | -19.797
| |  P99| 25ms| 10ms | -15ms | -60.729
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.574
| ChannelStore.AnalyticsCountAll |  Avg| 15ms| 0s | -15ms | -102.273
| |  P99| 25ms| 0s | -25ms | -100.779
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 31ms| 50ms | 19ms | 60.568
| |  P99| 39ms| 100ms | 61ms | 156.426
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 17ms | -3ms | -15.288
| |  P99| 111ms| 25ms | -86ms | -77.797
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 129ms| 114ms | -15ms | -11.624
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 15ms | 1ms | 7.039
| |  P99| 49ms| 94ms | 45ms | 91.973
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 43ms | 1ms | 2.368
| ChannelStore.GetChannelUnread |  Avg| 1ms| 2ms | 1ms | 71.575
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 31ms | -4ms | -11.538
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.709
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 41ms | 3ms | 7.860
| ChannelStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 34ms | 3ms | 9.629
| ChannelStore.GetMemberCount |  Avg| 15ms| 14ms | -1ms | -6.825
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 28ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 0s | -3ms | -93.603
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 36ms| 34ms | -2ms | -5.524
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 12ms | -1ms | -7.535
| |  P99| 42ms| 25ms | -17ms | -40.374
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.073
| ChannelStore.GetTeamChannels |  Avg| 10ms| 13ms | 3ms | 31.454
| |  P99| 10ms| 24ms | 14ms | 140.612
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 10ms | 1ms | 10.739
| |  P99| 24ms| 38ms | 14ms | 58.801
| ChannelStore.SaveMember |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 194ms| 198ms | 4ms | 2.057
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.016
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 19.382
| ChannelStore.UpdateSidebarCategories |  Avg| 33ms| 37ms | 4ms | 12.184
| |  P99| 50ms| 231ms | 181ms | 363.819
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 137.914
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 0s | -3ms | -111.058
| |  P99| 5ms| 0s | -5ms | -100.920
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 95.688
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.979
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.092
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 2ms | 1ms | 67.373
| |  P99| 5ms| 8ms | 3ms | 60.295
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.672
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.001
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 37ms | 6ms | 19.139
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.142
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 0s | -2ms | -131.094
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 22ms | 5ms | 29.137
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -128.211
| |  P99| 7ms| 0s | -7ms | -102.903
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.158
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 68.138
| |  P99| 5ms| 26ms | 21ms | 420.042
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 126.582
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 129.870
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.217
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.782
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -133.023
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -26.574
| |  P99| 21ms| 5ms | -16ms | -76.917
| PluginStore.Delete |  Avg| 2ms| 0s | -2ms | -114.376
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -85.362
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 0s | -4ms | -96.418
| |  P99| 10ms| 0s | -10ms | -102.564
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -56.920
| |  P99| 31ms| 10ms | -21ms | -66.918
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.377
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 2ms| 449ms | 447ms | 27987.878
| |  P99| 5ms| 498ms | 493ms | 9957.705
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 0s | -1ms | -87.429
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.Delete |  Avg| 13ms| 12ms | -1ms | -7.698
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.533
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.227
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 2ms | -1ms | -36.866
| |  P99| 10ms| 5ms | -5ms | -51.280
| PostStore.GetPostReminders |  Avg| 5ms| 7ms | 2ms | 36.665
| |  P99| 10ms| 46ms | 36ms | 363.866
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 29ms| 29ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 83ms| 84ms | 1ms | 1.198
| |  P99| 916ms| 924ms | 8ms | 0.874
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.277
| PreferenceStore.Save |  Avg| 12ms| 13ms | 1ms | 8.246
| |  P99| 88ms| 90ms | 2ms | 2.260
| ProductNoticesStore.GetViews |  Avg| 2ms| 0s | -2ms | -129.067
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 43ms| 45ms | 2ms | 4.697
| |  P99| 236ms| 245ms | 9ms | 3.815
| PropertyFieldStore.SearchPropertyFields |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 36ms | 2ms | 5.900
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 14ms | -6ms | -29.647
| ReactionStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -24.611
| |  P99| 27ms| 10ms | -17ms | -61.999
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -73.613
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -147.095
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.800
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.452
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 343.434
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 6.874
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -75.576
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 55ms| 61ms | 6ms | 10.863
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 33ms | -1ms | -2.972
| SessionStore.GetSessionsExpired |  Avg| 1ms| 2ms | 1ms | 68.257
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 8ms | 1ms | 13.564
| |  P99| 48ms| 49ms | 1ms | 2.082
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 3ms | 1ms | 40.400
| |  P99| 27ms| 30ms | 3ms | 11.028
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 3ms| 4ms | 1ms | 29.132
| |  P99| 20ms| 21ms | 1ms | 5.099
| StatusStore.SaveOrUpdateMany |  Avg| 5ms| 6ms | 1ms | 19.070
| |  P99| 20ms| 24ms | 4ms | 20.101
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 18ms | 6ms | 51.502
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 30ms | -2ms | -6.235
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 0s | -1ms | -88.070
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.384
| TeamStore.GetActiveMemberCount |  Avg| 31ms| 32ms | 1ms | 3.204
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.077
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 32ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 9.143
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 34ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 31ms| 33ms | 2ms | 6.387
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 87ms| 90ms | 3ms | 3.452
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 39.060
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.067
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.823
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.205
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.067
| ThreadStore.MaintainMembership |  Avg| 5ms| 6ms | 1ms | 18.242
| |  P99| 17ms| 20ms | 3ms | 17.797
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -92.829
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -65.623
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 12ms| 0s | -12ms | -102.361
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 0s | -2ms | -85.059
| |  P99| 5ms| 0s | -5ms | -100.987
| UserStore.AutocompleteUsersInChannel |  Avg| 33ms| 34ms | 1ms | 3.011
| |  P99| 161ms| 174ms | 13ms | 8.073
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.054
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 165ms| 166ms | 1ms | 0.605
| |  P99| 487ms| 488ms | 1ms | 0.206
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 77.637
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.044
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -97.375
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.571
| UserStore.GetProfilesInChannel |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.357
| UserStore.IsEmpty |  Avg| 1ms| 2ms | 1ms | 69.128
| |  P99| 20ms| 21ms | 1ms | 5.106
| UserStore.Save |  Avg| 144ms| 145ms | 1ms | 0.693
| |  P99| 298ms| 355ms | 57ms | 19.105
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.020
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 38ms| 22ms | -16ms | -41.833
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.670
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 32ms| 32ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 6ms | 1ms | 18.341
| |  P99| 27ms| 27ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.845
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 157ms| 164ms | 7ms | 4.464
| | P99| 250ms| 368ms | 118ms | 47.215
| addTeamMember | Avg| 712ms| 717ms | 5ms | 0.702
| | P99| 2.389s| 2.391s | 2ms | 0.084
| autocompleteChannelsForTeamForSearch | Avg| 31ms| 50ms | 19ms | 60.418
| | P99| 42ms| 100ms | 58ms | 138.929
| autocompleteUsers | Avg| 30ms| 31ms | 1ms | 3.328
| | P99| 132ms| 149ms | 17ms | 12.915
| createChannel | Avg| 153ms| 179ms | 26ms | 16.939
| | P99| 249ms| 490ms | 241ms | 96.982
| createChannelBookmark | Avg| 14ms| 12ms | -2ms | -14.695
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 168ms| 164ms | -4ms | -2.380
| | P99| 279ms| 308ms | 29ms | 10.383
| createGroupChannel | Avg| 250ms| 253ms | 3ms | 1.201
| | P99| 496ms| 780ms | 284ms | 57.307
| createPost | Avg| 138ms| 142ms | 4ms | 2.893
| | P99| 684ms| 739ms | 55ms | 8.044
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.285
| createUser | Avg| 216ms| 221ms | 5ms | 2.310
| | P99| 496ms| 538ms | 42ms | 8.459
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 18ms| 21ms | 3ms | 16.290
| | P99| 25ms| 48ms | 23ms | 92.555
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 40ms| 41ms | 1ms | 2.500
| getAnalytics | Avg| 27ms| 0s | -27ms | -100.551
| | P99| 49ms| 0s | -49ms | -99.122
| getCategoriesForTeamForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 59ms| 59ms | 0s | 0.000
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 12ms| 21ms | 9ms | 76.273
| getChannelMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 67ms| 77ms | 10ms | 14.927
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getChannelMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 37ms| 35ms | -2ms | -5.411
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 33ms| 33ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getChannelsForUser | Avg| 4ms| 3ms | -1ms | -27.341
| | P99| 35ms| 31ms | -4ms | -11.294
| getClientConfig | Avg| 9ms| 8ms | -1ms | -11.764
| | P99| 81ms| 77ms | -4ms | -4.959
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 10ms | 5ms | 95.383
| getFilePreview | Avg| 40ms| 39ms | -1ms | -2.519
| | P99| 96ms| 95ms | -1ms | -1.039
| getFileThumbnail | Avg| 34ms| 33ms | -1ms | -2.942
| | P99| 95ms| 93ms | -2ms | -2.115
| getFilteredUsersStats | Avg| 9ms| 0s | -9ms | -100.843
| | P99| 10ms| 0s | -10ms | -100.486
| getGroups | Avg| 2ms| 0s | -2ms | -87.879
| | P99| 5ms| 0s | -5ms | -101.010
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -112.692
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -114.572
| | P99| 7ms| 0s | -7ms | -102.903
| getPostThread | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 93ms| 94ms | 1ms | 1.073
| getPostsForChannelAroundLastUnread | Avg| 19ms| 20ms | 1ms | 5.164
| | P99| 161ms| 177ms | 16ms | 9.920
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 39ms| 41ms | 2ms | 5.134
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -105.304
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 2ms| 0s | -2ms | -116.060
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 113ms| 117ms | 4ms | 3.533
| | P99| 498ms| 770ms | 272ms | 54.594
| getPublicChannelsForTeam | Avg| 14ms| 13ms | -1ms | -7.052
| | P99| 42ms| 25ms | -17ms | -40.374
| getRolesByNames | Avg| 2ms| 0s | -2ms | -102.440
| | P99| 5ms| 0s | -5ms | -101.010
| getServerLimits | Avg| 10ms| 0s | -10ms | -104.419
| | P99| 24ms| 0s | -24ms | -98.361
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.039
| getTeamMembersForUser | Avg| 4ms| 3ms | -1ms | -28.078
| | P99| 40ms| 39ms | -1ms | -2.514
| getTeamScheduledPosts | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 55ms| 57ms | 2ms | 3.640
| getTeamStats | Avg| 31ms| 33ms | 2ms | 6.353
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 33ms| 36ms | 3ms | 8.982
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 28ms| 31ms | 3ms | 10.673
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 49ms| 50ms | 1ms | 2.046
| getUserByUsername | Avg| 2ms| 0s | -2ms | -106.890
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 49ms| 47ms | -2ms | -4.063
| getUsersByGroupChannelIds | Avg| 5ms| 0s | -5ms | -110.871
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -16.171
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 68ms| 0s | -68ms | -99.589
| | P99| 100ms| 0s | -100ms | -100.479
| listCPAFields | Avg| 3ms| 4ms | 1ms | 29.221
| | P99| 42ms| 43ms | 1ms | 2.397
| listCPAValues | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 14ms | -6ms | -29.647
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 11ms | 0s | 0.000
| login | Avg| 147ms| 152ms | 5ms | 3.409
| | P99| 931ms| 961ms | 30ms | 3.223
| logout | Avg| 18ms| 23ms | 5ms | 27.712
| | P99| 25ms| 93ms | 68ms | 273.642
| patchPost | Avg| 21ms| 22ms | 1ms | 4.673
| | P99| 38ms| 46ms | 8ms | 21.096
| removeUserCustomStatus | Avg| 106ms| 111ms | 5ms | 4.732
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 29ms| 35ms | 6ms | 20.986
| searchAllChannels | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 14ms | 2ms | 17.192
| searchPostsInTeam | Avg| 92ms| 91ms | -1ms | -1.082
| | P99| 916ms| 929ms | 13ms | 1.419
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -2.017
| setPostReminder | Avg| 17ms| 16ms | -1ms | -5.874
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 48ms| 52ms | 4ms | 8.323
| | P99| 98ms| 231ms | 133ms | 135.712
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 4ms| 0s | -4ms | -90.194
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 29ms| 28ms | -1ms | -3.440
| | P99| 50ms| 50ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 450ms| 453ms | 3ms | 0.666
| | P99| 1.59s| 995ms | -595ms | -37.423
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 15ms| 15ms | 0s | 0.000
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 34ms| 36ms | 2ms | 5.941
