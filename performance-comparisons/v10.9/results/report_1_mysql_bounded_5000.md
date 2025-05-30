### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 1ms | 4ms | 3ms | 215.83
| PostStore.AnalyticsPostCount | avg | 200ms | 488ms | 288ms | 144.20
| ChannelStore.GetTeamChannels | avg | 22ms | 29ms | 7ms | 32.01
| PostStore.SearchPostsForUser | avg | 47ms | 61ms | 14ms | 30.09
| ChannelStore.AutocompleteInTeamForSearch | avg | 234ms | 283ms | 49ms | 20.96
| TeamStore.GetTotalMemberCount | avg | 73ms | 83ms | 10ms | 13.67
| UserStore.Count | avg | 53ms | 57ms | 4ms | 7.60
| UserStore.GetAllProfilesInChannel | avg | 184ms | 189ms | 5ms | 2.72
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostReminderMetadata | p99 | 5ms | 45ms | 40ms | 808.08
| JobStore.GetCountByStatusAndType | p99 | 5ms | 38ms | 33ms | 666.67
| PostStore.SearchPostsForUser | p99 | 342ms | 1.432s | 1.09s | 318.28
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 18ms | 13ms | 261.11
| StatusStore.UpdateExpiredDNDStatuses | p99 | 12ms | 28ms | 16ms | 137.34
| JobStore.Save | p99 | 9ms | 21ms | 12ms | 135.21
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 101.01
| PostPriorityStore.GetForPost | p99 | 10ms | 20ms | 10ms | 100.75
| ChannelStore.GetTeamChannels | p99 | 25ms | 50ms | 25ms | 100.57
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 10ms | 5ms | 100.06
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateStatus | p99 | 5ms | 9ms | 4ms | 80.81
| RoleStore.GetByNames | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.Update | p99 | 25ms | 44ms | 19ms | 76.46
| JobStore.UpdateOptimistically | p99 | 5ms | 8ms | 3ms | 60.58
| UserStore.GetUnreadCount | p99 | 14ms | 22ms | 8ms | 57.88
| ClusterDiscoveryStore.SetLastPingAt | p99 | 8ms | 12ms | 4ms | 49.69
| PostStore.Save | p99 | 25ms | 33ms | 8ms | 32.04
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 9ms | 11ms | 2ms | 22.67
| ChannelStore.GetChannelsByUser | p99 | 10ms | 12ms | 2ms | 20.04
| FileInfoStore.AttachToPost | p99 | 11ms | 13ms | 2ms | 17.39
| UserStore.AutocompleteUsersInChannel | p99 | 332ms | 378ms | 46ms | 13.84
| ChannelStore.GetPublicChannelsForTeam | p99 | 19ms | 21ms | 2ms | 10.41
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.306s | 2.418s | 112ms | 4.86
| PostStore.AnalyticsPostCountByTeam | p99 | 985ms | 995ms | 10ms | 1.02
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMany | avg | 2ms | 0s | -2ms | -101.92
| ComplianceStore.MessageExport | avg | 4ms | 0s | -4ms | -101.50
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | avg | 232ms | 0s | -232ms | -99.90
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 303ms | 0s | -303ms | -99.84
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -99.25
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -91.01
| ProductNoticesStore.GetViews | avg | 2ms | 0s | -2ms | -89.61
| CommandWebhookStore.Cleanup | avg | 4ms | 1ms | -3ms | -76.11
| UserStore.AnalyticsActiveCount | avg | 125ms | 33ms | -92ms | -73.75
| StatusStore.SaveOrUpdate | avg | 10ms | 3ms | -7ms | -67.24
| TeamStore.AnalyticsTeamCount | avg | 5ms | 2ms | -3ms | -62.84
| ChannelBookmarkStore.Save | avg | 12ms | 9ms | -3ms | -25.97
| ChannelStore.UpdateSidebarCategories | avg | 25ms | 21ms | -4ms | -16.17
| ChannelStore.Autocomplete | avg | 956ms | 943ms | -13ms | -1.36
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 10ms | 0s | -10ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -100.77
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 498ms | 0s | -498ms | -100.10
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring | p99 | 249ms | 0s | -249ms | -100.05
| StatusStore.SaveOrUpdate | p99 | 203ms | 10ms | -193ms | -95.28
| TeamStore.AnalyticsTeamCount | p99 | 25ms | 5ms | -20ms | -81.47
| UserStore.GetByUsername | p99 | 26ms | 5ms | -21ms | -80.72
| UserStore.AnalyticsActiveCount | p99 | 248ms | 50ms | -198ms | -79.68
| ScheduledPostStore.CreateScheduledPost | p99 | 23ms | 5ms | -18ms | -77.59
| FileInfoStore.SetContent | p99 | 49ms | 19ms | -30ms | -61.53
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.51
| PostStore.AnalyticsPostCount | p99 | 985ms | 498ms | -487ms | -49.42
| ChannelStore.UpdateSidebarCategories | p99 | 49ms | 25ms | -24ms | -48.63
| FileInfoStore.GetByIds | p99 | 9ms | 5ms | -4ms | -47.04
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.96
| LinkMetadataStore.Save | p99 | 8ms | 5ms | -3ms | -38.22
| GroupStore.GetByName | p99 | 12ms | 8ms | -4ms | -32.83
| StatusStore.Get | p99 | 10ms | 7ms | -3ms | -30.93
| SessionStore.GetLRUSessions | p99 | 10ms | 7ms | -3ms | -30.78
| JobStore.GetAllByStatus | p99 | 7ms | 5ms | -2ms | -30.69
| ChannelStore.SearchGroupChannels | p99 | 7ms | 5ms | -2ms | -27.36
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 10ms | 8ms | -2ms | -20.82
| FileInfoStore.Save | p99 | 12ms | 10ms | -2ms | -16.98
| ChannelStore.GetMembersForUserWithPagination | p99 | 15ms | 13ms | -2ms | -12.94
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 85ms | 77ms | -8ms | -9.44
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 0s | 4ms | 4ms | 1752.97
| searchPostsInTeam | avg | 52ms | 66ms | 14ms | 27.03
| createChannel | avg | 164ms | 207ms | 43ms | 26.20
| setPostReminder | avg | 15ms | 19ms | 4ms | 26.07
| autocompleteChannelsForTeamForSearch | avg | 234ms | 283ms | 49ms | 20.95
| logout | avg | 18ms | 20ms | 2ms | 10.87
| removeUserCustomStatus | avg | 85ms | 93ms | 8ms | 9.40
| autocompleteUsers | avg | 108ms | 110ms | 2ms | 1.85
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 432ms | 1.432s | 1s | 231.22
| setPostReminder | p99 | 25ms | 48ms | 23ms | 92.54
| addTeamMember | p99 | 997ms | 1.735s | 738ms | 74.03
| updatePreferences | p99 | 10ms | 16ms | 6ms | 60.22
| getTeamMember | p99 | 5ms | 7ms | 2ms | 40.16
| autocompleteUsers | p99 | 271ms | 344ms | 73ms | 26.94
| getAllTeams | p99 | 10ms | 12ms | 2ms | 20.02
| getPostsForChannel | p99 | 116ms | 134ms | 18ms | 15.48
| getPreferences | p99 | 13ms | 15ms | 2ms | 15.08
| saveReaction | p99 | 19ms | 21ms | 2ms | 10.48
| autocompleteChannelsForTeamForSearch | p99 | 2.306s | 2.418s | 112ms | 4.86
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 3ms | 0s | -3ms | -118.28
| getGroups | avg | 3ms | 0s | -3ms | -115.59
| getFilteredUsersStats | avg | 19ms | 0s | -19ms | -102.47
| getAnalytics | avg | 549ms | 0s | -549ms | -99.99
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -88.34
| getJobsByType | avg | 2ms | 0s | -2ms | -86.06
| getClientLicense | avg | 2ms | 0s | -2ms | -82.37
| createChannelBookmark | avg | 15ms | 12ms | -3ms | -19.74
| updateCategoriesForTeamForUser | avg | 37ms | 31ms | -6ms | -16.27
| createGroupChannel | avg | 206ms | 198ms | -8ms | -3.89
| getProfileImage | avg | 70ms | 68ms | -2ms | -2.86
| searchAllChannels | avg | 956ms | 942ms | -14ms | -1.46
| createPost | avg | 144ms | 142ms | -2ms | -1.39
| uploadFileStream | avg | 362ms | 357ms | -5ms | -1.38
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getJobsByType | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -100.77
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.53
| getAnalytics | p99 | 995ms | 0s | -995ms | -100.00
| getClientLicense | p99 | 24ms | 5ms | -19ms | -78.35
| createSchedulePost | p99 | 23ms | 9ms | -14ms | -60.35
| getChannel | p99 | 18ms | 11ms | -7ms | -39.83
| getUser | p99 | 13ms | 10ms | -3ms | -22.34
| getChannelMembersForUser | p99 | 15ms | 13ms | -2ms | -13.23
| getTeamScheduledPosts | p99 | 20ms | 18ms | -2ms | -10.21
| createGroupChannel | p99 | 490ms | 479ms | -11ms | -2.24
| createPost | p99 | 744ms | 731ms | -13ms | -1.75
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.408
| BotStore.Get |  Avg| 3ms| 2ms | -1ms | -37.786
| |  P99| 9ms| 5ms | -4ms | -43.956
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -99.251
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 12ms| 9ms | -3ms | -25.967
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.GetChannelsWithActivityDuring |  Avg| 232ms| 0s | -232ms | -99.900
| |  P99| 249ms| 0s | -249ms | -100.054
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 303ms| 0s | -303ms | -99.836
| |  P99| 498ms| 0s | -498ms | -100.101
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.246
| ChannelStore.AnalyticsCountAll |  Avg| 148ms| 149ms | 1ms | 0.675
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 956ms| 943ms | -13ms | -1.360
| |  P99| 2.459s| 2.458s | -1ms | -0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 234ms| 283ms | 49ms | 20.956
| |  P99| 2.306s| 2.418s | 112ms | 4.857
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 15ms| 16ms | 1ms | 6.564
| |  P99| 45ms| 45ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 13ms| 14ms | 1ms | 7.628
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 14ms | 1ms | 7.477
| |  P99| 85ms| 77ms | -8ms | -9.444
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.915
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 3ms | 1ms | 40.390
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.039
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.059
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMany |  Avg| 2ms| 0s | -2ms | -101.919
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.304
| ChannelStore.GetMemberCount |  Avg| 62ms| 63ms | 1ms | 1.601
| |  P99| 245ms| 246ms | 1ms | 0.408
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -12.937
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 261.115
| ChannelStore.GetPublicChannelsForTeam |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.414
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 4ms | -1ms | -21.158
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 22ms| 29ms | 7ms | 32.012
| |  P99| 25ms| 50ms | 25ms | 100.565
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.105
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.023
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.363
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 25ms| 21ms | -4ms | -16.173
| |  P99| 49ms| 25ms | -24ms | -48.632
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 12ms | 4ms | 49.692
| CommandWebhookStore.Cleanup |  Avg| 4ms| 1ms | -3ms | -76.113
| |  P99| 10ms| 5ms | -5ms | -50.505
| ComplianceStore.MessageExport |  Avg| 4ms| 0s | -4ms | -101.503
| |  P99| 10ms| 0s | -10ms | -101.010
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.695
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 17.392
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -47.044
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.983
| FileInfoStore.SetContent |  Avg| 8ms| 7ms | -1ms | -12.704
| |  P99| 49ms| 19ms | -30ms | -61.531
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 22.674
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 8ms | -4ms | -32.834
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.689
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -91.007
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 49.394
| |  P99| 5ms| 38ms | 33ms | 666.667
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.057
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 30.951
| |  P99| 9ms| 21ms | 12ms | 135.211
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.577
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.UpdateStatusOptimistically |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -82.734
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.216
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.386
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 100.752
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 200ms| 488ms | 288ms | 144.195
| |  P99| 985ms| 498ms | -487ms | -49.424
| PostStore.AnalyticsPostCountByTeam |  Avg| 504ms| 503ms | -1ms | -0.198
| |  P99| 985ms| 995ms | 10ms | 1.015
| PostStore.Delete |  Avg| 12ms| 13ms | 1ms | 8.213
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.680
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 48.029
| |  P99| 5ms| 45ms | 40ms | 808.081
| PostStore.GetPostReminders |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.473
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 11ms | 1ms | 9.597
| |  P99| 25ms| 33ms | 8ms | 32.044
| PostStore.SearchPostsForUser |  Avg| 47ms| 61ms | 14ms | 30.086
| |  P99| 342ms| 1.432s | 1.09s | 318.283
| PostStore.SetPostReminder |  Avg| 5ms| 6ms | 1ms | 18.424
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 14ms | 1ms | 7.665
| |  P99| 25ms| 44ms | 19ms | 76.459
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.730
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 2ms | 1ms | 71.503
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 0s | -2ms | -89.611
| |  P99| 5ms| 0s | -5ms | -100.772
| ProductNoticesStore.View |  Avg| 22ms| 23ms | 1ms | 4.621
| |  P99| 71ms| 72ms | 1ms | 1.407
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -88.503
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -110.305
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 3ms | -1ms | -26.372
| |  P99| 23ms| 5ms | -18ms | -77.589
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.816
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 2ms | 1ms | 75.216
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.777
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 4ms | 1ms | 31.746
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.993
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.602
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.927
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 10ms| 3ms | -7ms | -67.236
| |  P99| 203ms| 10ms | -193ms | -95.280
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 6ms | 1ms | 20.324
| |  P99| 12ms| 28ms | 16ms | 137.339
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 5ms| 2ms | -3ms | -62.844
| |  P99| 25ms| 5ms | -20ms | -81.467
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 97ms| 97ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.560
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.906
| TeamStore.GetTotalMemberCount |  Avg| 73ms| 83ms | 10ms | 13.667
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.362
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.337
| TokenStore.Cleanup |  Avg| 1ms| 4ms | 3ms | 215.825
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 125ms| 33ms | -92ms | -73.747
| |  P99| 248ms| 50ms | -198ms | -79.678
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 128ms| 129ms | 1ms | 0.784
| |  P99| 332ms| 378ms | 46ms | 13.844
| UserStore.Count |  Avg| 53ms| 57ms | 4ms | 7.598
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.477
| UserStore.GetAllProfilesInChannel |  Avg| 184ms| 189ms | 5ms | 2.716
| |  P99| 494ms| 495ms | 1ms | 0.202
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -38.950
| |  P99| 26ms| 5ms | -21ms | -80.724
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 23.650
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 6ms | 1ms | 20.751
| |  P99| 14ms| 22ms | 8ms | 57.884
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 63ms| 63ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 240ms| 241ms | 1ms | 0.416
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.875
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.093
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.323
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.656
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 141ms| 142ms | 1ms | 0.707
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 613ms| 619ms | 6ms | 0.980
| | P99| 997ms| 1.735s | 738ms | 74.033
| autocompleteChannelsForTeamForSearch | Avg| 234ms| 283ms | 49ms | 20.950
| | P99| 2.306s| 2.418s | 112ms | 4.857
| autocompleteUsers | Avg| 108ms| 110ms | 2ms | 1.851
| | P99| 271ms| 344ms | 73ms | 26.936
| createCategoryForTeamForUser | Avg| 16ms| 17ms | 1ms | 6.335
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 164ms| 207ms | 43ms | 26.196
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 15ms| 12ms | -3ms | -19.741
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 133ms| 133ms | 0s | 0.000
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 206ms| 198ms | -8ms | -3.888
| | P99| 490ms| 479ms | -11ms | -2.245
| createPost | Avg| 144ms| 142ms | -2ms | -1.390
| | P99| 744ms| 731ms | -13ms | -1.748
| createSchedulePost | Avg| 4ms| 3ms | -1ms | -23.131
| | P99| 23ms| 9ms | -14ms | -60.347
| createUser | Avg| 93ms| 92ms | -1ms | -1.071
| | P99| 244ms| 243ms | -1ms | -0.410
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 20ms| 19ms | -1ms | -5.113
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 11ms | 1ms | 10.002
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.019
| getAnalytics | Avg| 549ms| 0s | -549ms | -99.987
| | P99| 995ms| 0s | -995ms | -100.000
| getCategoriesForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 5ms| 6ms | 1ms | 18.658
| | P99| 18ms| 11ms | -7ms | -39.829
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 5.063
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.020
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 13ms | -2ms | -13.232
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 206ms| 207ms | 1ms | 0.484
| getChannelUnread | Avg| 2ms| 3ms | 1ms | 41.408
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.470
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| getClientConfig | Avg| 4ms| 5ms | 1ms | 23.216
| | P99| 19ms| 19ms | 0s | 0.000
| getClientLicense | Avg| 2ms| 0s | -2ms | -82.368
| | P99| 24ms| 5ms | -19ms | -78.351
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 93ms| 92ms | -1ms | -1.074
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 86ms| 85ms | -1ms | -1.158
| getFilteredUsersStats | Avg| 19ms| 0s | -19ms | -102.470
| | P99| 25ms| 0s | -25ms | -100.531
| getGroups | Avg| 3ms| 0s | -3ms | -115.585
| | P99| 5ms| 0s | -5ms | -101.010
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -88.342
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -86.058
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 12ms| 11ms | -1ms | -8.681
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 18ms| 19ms | 1ms | 5.465
| | P99| 116ms| 134ms | 18ms | 15.476
| getPostsForChannelAroundLastUnread | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 49ms| 50ms | 1ms | 2.026
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 15ms | 2ms | 15.084
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -69.947
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 3ms| 0s | -3ms | -118.282
| | P99| 5ms| 0s | -5ms | -100.772
| getProfileImage | Avg| 70ms| 68ms | -2ms | -2.859
| | P99| 249ms| 248ms | -1ms | -0.402
| getPublicChannelsForTeam | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.524
| getRolesByNames | Avg| 0s| 4ms | 4ms | 1752.967
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.164
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 12ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 20ms| 18ms | -2ms | -10.207
| getTeamStats | Avg| 98ms| 97ms | -1ms | -1.025
| | P99| 100ms| 100ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -22.341
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 236ms| 237ms | 1ms | 0.424
| logout | Avg| 18ms| 20ms | 2ms | 10.866
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 27ms| 28ms | 1ms | 3.659
| | P99| 50ms| 50ms | 0s | 0.000
| removeUserCustomStatus | Avg| 85ms| 93ms | 8ms | 9.401
| | P99| 245ms| 245ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 19ms| 21ms | 2ms | 10.480
| searchAllChannels | Avg| 956ms| 942ms | -14ms | -1.465
| | P99| 2.459s| 2.458s | -1ms | -0.041
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -13.682
| searchPostsInTeam | Avg| 52ms| 66ms | 14ms | 27.027
| | P99| 432ms| 1.432s | 1s | 231.220
| searchUsers | Avg| 57ms| 57ms | 0s | 0.000
| | P99| 241ms| 242ms | 1ms | 0.415
| setPostReminder | Avg| 15ms| 19ms | 4ms | 26.070
| | P99| 25ms| 48ms | 23ms | 92.539
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 37ms| 31ms | -6ms | -16.273
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 60.222
| updateReadStateThreadByUser | Avg| 25ms| 24ms | -1ms | -4.080
| | P99| 50ms| 49ms | -1ms | -2.019
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 362ms| 357ms | -5ms | -1.383
| | P99| 976ms| 977ms | 1ms | 0.102
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
