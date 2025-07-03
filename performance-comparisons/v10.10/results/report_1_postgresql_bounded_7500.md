### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 3ms | 260ms | 257ms | 7793.59
| UserStore.GetProfilesInChannel | avg | 12ms | 53ms | 41ms | 340.43
| ThreadStore.MarkAllAsReadByChannels | avg | 3ms | 5ms | 2ms | 61.12
| UserStore.Count | avg | 10ms | 12ms | 2ms | 19.38
| ChannelStore.UpdateSidebarCategories | avg | 43ms | 47ms | 4ms | 9.25
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 498ms | 493ms | 9958.01
| UserStore.GetProfilesInChannel | p99 | 25ms | 246ms | 221ms | 889.34
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 43ms | 34ms | 388.59
| UserStore.Update | p99 | 22ms | 60ms | 38ms | 173.52
| RoleStore.ChannelHigherScopedPermissions | p99 | 8ms | 20ms | 12ms | 150.59
| JobStore.GetAllByStatus | p99 | 9ms | 20ms | 11ms | 116.34
| JobStore.UpdateOptimistically | p99 | 9ms | 18ms | 9ms | 98.18
| JobStore.Save | p99 | 9ms | 18ms | 9ms | 96.95
| UserStore.Count | p99 | 25ms | 49ms | 24ms | 96.69
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateStatus | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.AutocompleteInTeamForSearch | p99 | 50ms | 87ms | 37ms | 74.64
| JobStore.GetCountByStatusAndType | p99 | 5ms | 8ms | 3ms | 60.61
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 8ms | 3ms | 60.01
| PostStore.Update | p99 | 25ms | 39ms | 14ms | 56.33
| ChannelStore.Save | p99 | 31ms | 45ms | 14ms | 44.45
| ChannelStore.GetSidebarCategory | p99 | 23ms | 25ms | 2ms | 8.58
| ChannelStore.GetByName | p99 | 36ms | 39ms | 3ms | 8.25
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 118ms | 126ms | 8ms | 6.78
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | avg | 2ms | 0s | -2ms | -126.91
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 0s | -2ms | -112.79
| RetentionPolicyStore.GetCount | avg | 2ms | 0s | -2ms | -111.10
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -110.35
| PluginStore.Get | avg | 2ms | 0s | -2ms | -102.94
| ProductNoticesStore.GetViews | avg | 2ms | 0s | -2ms | -101.60
| PropertyFieldStore.SearchPropertyFields | avg | 2ms | 0s | -2ms | -100.33
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 5ms | 0s | -5ms | -98.77
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -98.66
| UserStore.AnalyticsActiveCount | avg | 14ms | 0s | -14ms | -98.18
| ChannelStore.AnalyticsCountAll | avg | 19ms | 0s | -19ms | -98.11
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -96.68
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -95.84
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -91.90
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -91.09
| ComplianceStore.MessageExport | avg | 3ms | 0s | -3ms | -89.98
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 0s | -2ms | -88.59
| StatusStore.SaveOrUpdate | avg | 18ms | 4ms | -14ms | -75.81
| RoleStore.GetByNames | avg | 4ms | 2ms | -2ms | -52.39
| TeamStore.GetTotalMemberCount | avg | 27ms | 19ms | -8ms | -29.58
| PostStore.SearchPostsForUser | avg | 92ms | 82ms | -10ms | -10.84
| PostStore.Delete | avg | 19ms | 17ms | -2ms | -10.59
| TeamStore.GetActiveMemberCount | avg | 41ms | 38ms | -3ms | -7.39
| ChannelStore.AutocompleteInTeamForSearch | avg | 28ms | 26ms | -2ms | -7.26
| ProductNoticesStore.View | avg | 39ms | 37ms | -2ms | -5.14
| UserStore.GetAllProfilesInChannel | avg | 156ms | 150ms | -6ms | -3.84
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetAllByTypePage | p99 | 8ms | 0s | -8ms | -105.93
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 10ms | 0s | -10ms | -102.56
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| PropertyFieldStore.SearchPropertyFields | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.AnalyticsPostCountByTeam | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.92
| ComplianceStore.MessageExport | p99 | 5ms | 0s | -5ms | -100.86
| UserStore.AnalyticsActiveCount | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.AnalyticsCountAll | p99 | 25ms | 0s | -25ms | -100.60
| StatusStore.SaveOrUpdate | p99 | 248ms | 16ms | -232ms | -93.51
| RoleStore.GetByNames | p99 | 24ms | 5ms | -19ms | -79.83
| PostPersistentNotificationStore.DeleteExpired | p99 | 21ms | 5ms | -16ms | -76.92
| TeamStore.GetTotalMemberCount | p99 | 97ms | 25ms | -72ms | -74.61
| StatusStore.UpdateExpiredDNDStatuses | p99 | 55ms | 18ms | -37ms | -66.67
| ChannelStore.UpdateSidebarCategories | p99 | 223ms | 90ms | -133ms | -59.64
| PostStore.GetPostReminders | p99 | 22ms | 10ms | -12ms | -53.45
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 5ms | -5ms | -52.08
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 5ms | -5ms | -52.08
| TeamStore.GetActiveMemberCount | p99 | 97ms | 50ms | -47ms | -48.70
| PostStore.Delete | p99 | 48ms | 25ms | -23ms | -47.92
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -46.51
| ScheduledPostStore.CreateScheduledPost | p99 | 9ms | 5ms | -4ms | -43.13
| FileInfoStore.GetByIds | p99 | 8ms | 5ms | -3ms | -38.33
| ClusterDiscoveryStore.SetLastPingAt | p99 | 21ms | 13ms | -8ms | -37.91
| UserStore.GetByUsername | p99 | 16ms | 10ms | -6ms | -37.68
| PostAcknowledgementStore.GetForPost | p99 | 16ms | 10ms | -6ms | -36.53
| ChannelStore.GetPublicChannelsForTeam | p99 | 50ms | 37ms | -13ms | -26.02
| PostPersistentNotificationStore.GetSingle | p99 | 8ms | 6ms | -2ms | -24.74
| DraftStore.GetDraftsForUser | p99 | 13ms | 10ms | -3ms | -22.58
| UserStore.Search | p99 | 64ms | 50ms | -14ms | -22.04
| ProductNoticesStore.View | p99 | 149ms | 118ms | -31ms | -20.80
| ThreadStore.GetMembershipForUser | p99 | 10ms | 8ms | -2ms | -20.69
| UserStore.GetUnreadCount | p99 | 20ms | 16ms | -4ms | -19.90
| DraftStore.Delete | p99 | 11ms | 9ms | -2ms | -17.68
| GroupStore.GetByName | p99 | 20ms | 17ms | -3ms | -15.33
| ChannelStore.UpdateLastViewedAt | p99 | 14ms | 12ms | -2ms | -14.73
| SessionStore.Save | p99 | 29ms | 25ms | -4ms | -13.58
| FileInfoStore.Save | p99 | 23ms | 20ms | -3ms | -13.25
| ChannelStore.SearchGroupChannels | p99 | 23ms | 20ms | -3ms | -13.08
| DraftStore.Upsert | p99 | 17ms | 15ms | -2ms | -12.11
| PostStore.GetPostIdAfterTime | p99 | 17ms | 15ms | -2ms | -11.64
| TeamStore.SaveMember | p99 | 78ms | 69ms | -9ms | -11.53
| FileInfoStore.SetContent | p99 | 35ms | 31ms | -4ms | -11.37
| UserStore.GetForLogin | p99 | 20ms | 18ms | -2ms | -10.16
| TeamStore.GetTeamsByUserId | p99 | 20ms | 18ms | -2ms | -10.12
| UserStore.UpdateLastLogin | p99 | 22ms | 20ms | -2ms | -9.08
| WebhookStore.GetOutgoingByTeam | p99 | 35ms | 32ms | -3ms | -8.67
| UserStore.AutocompleteUsersInChannel | p99 | 178ms | 167ms | -11ms | -6.17
| ChannelStore.CreateInitialSidebarCategories | p99 | 83ms | 78ms | -5ms | -6.02
| UserStore.GetAllProfilesInChannel | p99 | 477ms | 472ms | -5ms | -1.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 27ms | 32ms | 5ms | 18.64
| createUser | avg | 121ms | 141ms | 20ms | 16.56
| updateCategoriesForTeamForUser | avg | 59ms | 65ms | 6ms | 10.12
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | p99 | 5ms | 14ms | 9ms | 181.82
| logout | p99 | 50ms | 97ms | 47ms | 94.81
| createChannelBookmark | p99 | 25ms | 48ms | 23ms | 92.52
| autocompleteChannelsForTeamForSearch | p99 | 50ms | 87ms | 37ms | 74.61
| createGroupChannel | p99 | 497ms | 750ms | 253ms | 50.91
| saveReaction | p99 | 30ms | 38ms | 8ms | 26.23
| patchPost | p99 | 106ms | 119ms | 13ms | 12.25
| getChannelsForUser | p99 | 18ms | 20ms | 2ms | 10.89
| createUser | p99 | 368ms | 408ms | 40ms | 10.87
| addChannelMember | p99 | 480ms | 485ms | 5ms | 1.04
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 2ms | 0s | -2ms | -129.68
| getUserByUsername | avg | 3ms | 0s | -3ms | -119.31
| getFilteredUsersStats | avg | 11ms | 0s | -11ms | -103.15
| getAnalytics | avg | 45ms | 0s | -45ms | -99.31
| listCPAFields | avg | 2ms | 0s | -2ms | -97.72
| getProductNotices | avg | 2ms | 0s | -2ms | -94.86
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -89.52
| getJobsByType | avg | 2ms | 0s | -2ms | -84.97
| updateReadStateAllThreadsByUser | avg | 2ms | 0s | -2ms | -84.64
| followThreadByUser | avg | 17ms | 14ms | -3ms | -17.20
| removeUserCustomStatus | avg | 115ms | 98ms | -17ms | -14.75
| getProfileImage | avg | 98ms | 86ms | -12ms | -12.20
| searchPostsInTeam | avg | 99ms | 91ms | -8ms | -8.07
| getTeamStats | avg | 41ms | 38ms | -3ms | -7.28
| createDirectChannel | avg | 178ms | 169ms | -9ms | -5.07
| createChannel | avg | 207ms | 200ms | -7ms | -3.38
| addChannelMember | avg | 191ms | 185ms | -6ms | -3.14
| createGroupChannel | avg | 296ms | 291ms | -5ms | -1.69
| createPost | avg | 187ms | 184ms | -3ms | -1.60
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getJobsByType | p99 | 9ms | 0s | -9ms | -102.56
| getRolesByNames | p99 | 10ms | 0s | -10ms | -101.78
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getUserByUsername | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| listCPAFields | p99 | 5ms | 0s | -5ms | -100.91
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| getAnalytics | p99 | 50ms | 0s | -50ms | -100.46
| getTeamMember | p99 | 20ms | 9ms | -11ms | -54.86
| getChannelUnread | p99 | 10ms | 5ms | -5ms | -51.68
| followThreadByUser | p99 | 49ms | 25ms | -24ms | -49.48
| getTeamStats | p99 | 97ms | 50ms | -47ms | -48.70
| createChannel | p99 | 483ms | 249ms | -234ms | -48.50
| getDrafts | p99 | 15ms | 10ms | -5ms | -34.20
| searchUsers | p99 | 69ms | 55ms | -14ms | -20.41
| getPublicChannelsForTeam | p99 | 50ms | 42ms | -8ms | -16.01
| searchGroupChannels | p99 | 23ms | 20ms | -3ms | -13.08
| getPostThread | p99 | 45ms | 40ms | -5ms | -11.05
| autocompleteUsers | p99 | 152ms | 136ms | -16ms | -10.51
| getPostsForChannelAroundLastUnread | p99 | 78ms | 70ms | -8ms | -10.30
| getChannelMember | p99 | 41ms | 38ms | -3ms | -7.34
| getProfileImage | p99 | 479ms | 449ms | -30ms | -6.27
| createPost | p99 | 839ms | 827ms | -12ms | -1.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 4ms | -1ms | -21.947
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -96.683
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.006
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 0s | -19ms | -98.108
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Autocomplete |  Avg| 33ms| 32ms | -1ms | -3.020
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 28ms| 26ms | -2ms | -7.259
| |  P99| 50ms| 87ms | 37ms | 74.636
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 25ms | 1ms | 4.102
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 83ms| 78ms | -5ms | -6.016
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 16ms | 1ms | 6.514
| |  P99| 118ms| 126ms | 8ms | 6.777
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 39ms | 3ms | 8.251
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.889
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.498
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.309
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.441
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.697
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 5ms| 0s | -5ms | -98.772
| |  P99| 10ms| 0s | -10ms | -102.564
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.947
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 50ms| 37ms | -13ms | -26.020
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 15ms | 1ms | 7.313
| |  P99| 47ms| 48ms | 1ms | 2.122
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 8ms | 1ms | 15.333
| |  P99| 23ms| 25ms | 2ms | 8.584
| ChannelStore.GetTeamChannels |  Avg| 11ms| 12ms | 1ms | 9.391
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.257
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.504
| ChannelStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 31ms| 45ms | 14ms | 44.455
| ChannelStore.SaveMember |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 92ms| 92ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.081
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.728
| ChannelStore.UpdateSidebarCategories |  Avg| 43ms| 47ms | 4ms | 9.252
| |  P99| 223ms| 90ms | -133ms | -59.644
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 13ms | -8ms | -37.910
| CommandWebhookStore.Cleanup |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 0s | -3ms | -89.976
| |  P99| 5ms| 0s | -5ms | -100.859
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -17.679
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.085
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.580
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -12.107
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 8ms| 7ms | -1ms | -13.308
| |  P99| 23ms| 23ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.334
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.714
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.252
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.605
| |  P99| 35ms| 31ms | -4ms | -11.375
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.284
| GroupStore.GetByName |  Avg| 3ms| 2ms | -1ms | -39.908
| |  P99| 20ms| 17ms | -3ms | -15.326
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.642
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 0s | -2ms | -98.665
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 2ms| 3ms | 1ms | 43.268
| |  P99| 9ms| 20ms | 11ms | 116.340
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -91.903
| |  P99| 8ms| 0s | -8ms | -105.928
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.012
| JobStore.Save |  Avg| 4ms| 5ms | 1ms | 23.967
| |  P99| 9ms| 18ms | 9ms | 96.948
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 98.182
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -99.631
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.647
| LinkMetadataStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.338
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.892
| PluginStore.Get |  Avg| 2ms| 0s | -2ms | -102.939
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.533
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 2ms | -1ms | -35.145
| |  P99| 21ms| 5ms | -16ms | -76.923
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.745
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.729
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 3ms| 260ms | 257ms | 7793.592
| |  P99| 5ms| 498ms | 493ms | 9958.013
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 0s | -1ms | -77.743
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.Delete |  Avg| 19ms| 17ms | -2ms | -10.591
| |  P99| 48ms| 25ms | -23ms | -47.918
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.638
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.364
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.186
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.956
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 13ms | -1ms | -7.393
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 92ms| 82ms | -10ms | -10.836
| |  P99| 937ms| 931ms | -6ms | -0.640
| PostStore.SetPostReminder |  Avg| 9ms| 8ms | -1ms | -11.678
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 14ms| 15ms | 1ms | 7.011
| |  P99| 25ms| 39ms | 14ms | 56.330
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.085
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.071
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.092
| ProductNoticesStore.GetViews |  Avg| 2ms| 0s | -2ms | -101.603
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 39ms| 37ms | -2ms | -5.139
| |  P99| 149ms| 118ms | -31ms | -20.799
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 0s | -2ms | -100.333
| |  P99| 5ms| 0s | -5ms | -101.010
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -110.355
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 2ms| 0s | -2ms | -111.099
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 4ms | 1ms | 31.075
| |  P99| 8ms| 20ms | 12ms | 150.593
| RoleStore.GetByNames |  Avg| 4ms| 2ms | -2ms | -52.387
| |  P99| 24ms| 5ms | -19ms | -79.833
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.125
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.680
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -95.835
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 33ms| 33ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 3ms | 1ms | 40.215
| |  P99| 17ms| 18ms | 1ms | 5.833
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -37.961
| |  P99| 10ms| 9ms | -1ms | -10.163
| SessionStore.Remove |  Avg| 4ms| 3ms | -1ms | -27.805
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.581
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 18.045
| StatusStore.SaveOrUpdate |  Avg| 18ms| 4ms | -14ms | -75.808
| |  P99| 248ms| 16ms | -232ms | -93.514
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 3ms | -1ms | -27.193
| |  P99| 55ms| 18ms | -37ms | -66.667
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 0s | -2ms | -126.914
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.525
| TeamStore.GetActiveMemberCount |  Avg| 41ms| 38ms | -3ms | -7.389
| |  P99| 97ms| 50ms | -47ms | -48.703
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.305
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.119
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 27ms| 19ms | -8ms | -29.580
| |  P99| 97ms| 25ms | -72ms | -74.609
| TeamStore.SaveMember |  Avg| 26ms| 25ms | -1ms | -3.896
| |  P99| 78ms| 69ms | -9ms | -11.526
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.687
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.795
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.128
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.184
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.549
| ThreadStore.MaintainMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.169
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 5ms | 2ms | 61.120
| |  P99| 9ms| 43ms | 34ms | 388.589
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 0s | -2ms | -88.592
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 0s | -14ms | -98.179
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 0s | -2ms | -112.793
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 38ms| 37ms | -1ms | -2.652
| |  P99| 178ms| 167ms | -11ms | -6.166
| UserStore.Count |  Avg| 10ms| 12ms | 2ms | 19.378
| |  P99| 25ms| 49ms | 24ms | 96.689
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.833
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 156ms| 150ms | -6ms | -3.840
| |  P99| 477ms| 472ms | -5ms | -1.048
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.675
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.159
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -91.094
| |  P99| 5ms| 0s | -5ms | -100.924
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.761
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.261
| UserStore.GetProfilesInChannel |  Avg| 12ms| 53ms | 41ms | 340.434
| |  P99| 25ms| 246ms | 221ms | 889.336
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 22.446
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -19.900
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.270
| UserStore.Save |  Avg| 71ms| 71ms | 0s | 0.000
| |  P99| 202ms| 202ms | 0s | 0.000
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 64ms| 50ms | -14ms | -22.036
| UserStore.Update |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 60ms | 38ms | 173.516
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.083
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.637
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.051
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 32ms | -3ms | -8.670
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 191ms| 185ms | -6ms | -3.141
| | P99| 480ms| 485ms | 5ms | 1.042
| addTeamMember | Avg| 619ms| 619ms | 0s | 0.000
| | P99| 2.167s| 2.151s | -16ms | -0.738
| autocompleteChannelsForTeamForSearch | Avg| 28ms| 27ms | -1ms | -3.622
| | P99| 50ms| 87ms | 37ms | 74.613
| autocompleteUsers | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 152ms| 136ms | -16ms | -10.515
| createChannel | Avg| 207ms| 200ms | -7ms | -3.376
| | P99| 483ms| 249ms | -234ms | -48.497
| createChannelBookmark | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.520
| createDirectChannel | Avg| 178ms| 169ms | -9ms | -5.070
| | P99| 485ms| 483ms | -2ms | -0.412
| createGroupChannel | Avg| 296ms| 291ms | -5ms | -1.692
| | P99| 497ms| 750ms | 253ms | 50.906
| createPost | Avg| 187ms| 184ms | -3ms | -1.602
| | P99| 839ms| 827ms | -12ms | -1.430
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.283
| createUser | Avg| 121ms| 141ms | 20ms | 16.558
| | P99| 368ms| 408ms | 40ms | 10.870
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 26ms| 25ms | -1ms | -3.831
| | P99| 50ms| 49ms | -1ms | -2.020
| followThreadByUser | Avg| 17ms| 14ms | -3ms | -17.200
| | P99| 49ms| 25ms | -24ms | -49.484
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getAnalytics | Avg| 45ms| 0s | -45ms | -99.305
| | P99| 50ms| 0s | -50ms | -100.460
| getCategoriesForTeamForUser | Avg| 14ms| 15ms | 1ms | 6.920
| | P99| 48ms| 49ms | 1ms | 2.075
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.861
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 41ms| 38ms | -3ms | -7.337
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 15ms | 0s | 0.000
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 4.920
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 29ms| 30ms | 1ms | 3.507
| getChannelUnread | Avg| 3ms| 2ms | -1ms | -34.063
| | P99| 10ms| 5ms | -5ms | -51.680
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 14ms | -1ms | -6.780
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 20ms | 2ms | 10.885
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 40ms| 40ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 10ms | -5ms | -34.196
| getFilePreview | Avg| 39ms| 38ms | -1ms | -2.575
| | P99| 96ms| 95ms | -1ms | -1.045
| getFileThumbnail | Avg| 33ms| 32ms | -1ms | -3.074
| | P99| 90ms| 89ms | -1ms | -1.110
| getFilteredUsersStats | Avg| 11ms| 0s | -11ms | -103.151
| | P99| 25ms| 0s | -25ms | -100.604
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -89.521
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -84.971
| | P99| 9ms| 0s | -9ms | -102.565
| getPostThread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 45ms| 40ms | -5ms | -11.052
| getPostsForChannel | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 188ms| 188ms | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 78ms| 70ms | -8ms | -10.305
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -85.677
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 2ms| 0s | -2ms | -94.858
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 98ms| 86ms | -12ms | -12.205
| | P99| 479ms| 449ms | -30ms | -6.268
| getPublicChannelsForTeam | Avg| 15ms| 14ms | -1ms | -6.729
| | P99| 50ms| 42ms | -8ms | -16.012
| getRolesByNames | Avg| 2ms| 0s | -2ms | -129.682
| | P99| 10ms| 0s | -10ms | -101.779
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 9ms | -11ms | -54.856
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -3.953
| getTeamStats | Avg| 41ms| 38ms | -3ms | -7.285
| | P99| 97ms| 50ms | -47ms | -48.703
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.044
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 26ms| 26ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getUserByUsername | Avg| 3ms| 0s | -3ms | -119.306
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 2ms| 0s | -2ms | -97.716
| | P99| 5ms| 0s | -5ms | -100.914
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 64ms| 64ms | 0s | 0.000
| | P99| 248ms| 247ms | -1ms | -0.404
| logout | Avg| 27ms| 32ms | 5ms | 18.643
| | P99| 50ms| 97ms | 47ms | 94.812
| patchPost | Avg| 29ms| 28ms | -1ms | -3.460
| | P99| 106ms| 119ms | 13ms | 12.254
| removeUserCustomStatus | Avg| 115ms| 98ms | -17ms | -14.746
| | P99| 248ms| 246ms | -2ms | -0.807
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 30ms| 38ms | 8ms | 26.235
| searchAllChannels | Avg| 33ms| 32ms | -1ms | -3.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 20ms | -3ms | -13.081
| searchPostsInTeam | Avg| 99ms| 91ms | -8ms | -8.067
| | P99| 941ms| 940ms | -1ms | -0.106
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 69ms| 55ms | -14ms | -20.409
| setPostReminder | Avg| 20ms| 21ms | 1ms | 4.881
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 15ms| 14ms | -1ms | -6.843
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 59ms| 65ms | 6ms | 10.116
| | P99| 223ms| 221ms | -2ms | -0.897
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 2ms| 0s | -2ms | -84.645
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 41ms| 41ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 14ms | 9ms | 181.818
| uploadFileStream | Avg| 439ms| 436ms | -3ms | -0.683
| | P99| 993ms| 989ms | -4ms | -0.403
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.080
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 44ms| 43ms | -1ms | -2.254
