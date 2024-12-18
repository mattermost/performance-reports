### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 9ms | 20ms | 11ms | 116.21
| ChannelStore.GetMembers | avg | 2ms | 4ms | 2ms | 80.55
| PostStore.SearchPostsForUser | avg | 44ms | 68ms | 24ms | 55.04
| UserStore.Count | avg | 53ms | 59ms | 6ms | 11.22
| TeamStore.GetTotalMemberCount | avg | 82ms | 86ms | 4ms | 4.86
| UserStore.GetAllProfilesInChannel | avg | 249ms | 260ms | 11ms | 4.42
| TeamStore.GetActiveMemberCount | avg | 110ms | 114ms | 4ms | 3.64
| ChannelStore.Autocomplete | avg | 954ms | 972ms | 18ms | 1.89
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | p99 | 250ms | 1.368s | 1.118s | 447.46
| ChannelStore.GetSidebarCategory | p99 | 18ms | 44ms | 26ms | 148.56
| TeamStore.GetTotalMemberCount | p99 | 100ms | 236ms | 136ms | 136.68
| UserStore.Count | p99 | 99ms | 216ms | 117ms | 118.01
| ChannelStore.GetMembers | p99 | 5ms | 10ms | 5ms | 101.01
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.GetChannelsByUser | p99 | 5ms | 9ms | 4ms | 80.06
| StatusStore.SaveOrUpdate | p99 | 196ms | 353ms | 157ms | 79.93
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 88ms | 38ms | 76.38
| DraftStore.GetDraftsForUser | p99 | 7ms | 11ms | 4ms | 54.73
| PostPriorityStore.GetForPost | p99 | 5ms | 7ms | 2ms | 40.40
| PluginStore.List | p99 | 5ms | 7ms | 2ms | 40.40
| FileInfoStore.Save | p99 | 10ms | 14ms | 4ms | 40.40
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 5ms | 7ms | 2ms | 40.12
| TeamStore.GetTeamsByUserId | p99 | 5ms | 7ms | 2ms | 40.02
| ReactionStore.GetForPost | p99 | 9ms | 12ms | 3ms | 34.44
| PostStore.Update | p99 | 40ms | 44ms | 4ms | 10.00
| UserStore.AutocompleteUsersInChannel | p99 | 362ms | 383ms | 21ms | 5.79
| ProductNoticesStore.View | p99 | 92ms | 94ms | 2ms | 2.17
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -90.53
| TokenStore.Cleanup | avg | 4ms | 2ms | -2ms | -46.25
| ChannelStore.GetPublicChannelsForTeam | avg | 10ms | 8ms | -2ms | -20.56
| ChannelBookmarkStore.Save | avg | 13ms | 11ms | -2ms | -15.93
| ChannelStore.AutocompleteInTeamForSearch | avg | 221ms | 202ms | -19ms | -8.60
| PostStore.AnalyticsPostCount | avg | 742ms | 711ms | -31ms | -4.18
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 0s | -10ms | -101.52
| PostPersistentNotificationStore.Get | p99 | 40ms | 5ms | -35ms | -88.05
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 21ms | 5ms | -16ms | -74.77
| PostPersistentNotificationStore.DeleteExpired | p99 | 19ms | 5ms | -14ms | -74.27
| JobStore.GetCountByStatusAndType | p99 | 33ms | 9ms | -24ms | -73.28
| UserStore.GetMany | p99 | 19ms | 5ms | -14ms | -73.10
| JobStore.Save | p99 | 22ms | 8ms | -14ms | -64.67
| SessionStore.GetSessionsExpired | p99 | 10ms | 5ms | -5ms | -52.63
| TokenStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| FileInfoStore.GetByIds | p99 | 10ms | 5ms | -5ms | -48.32
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -45.45
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 9ms | 5ms | -4ms | -45.45
| JobStore.UpdateStatus | p99 | 9ms | 5ms | -4ms | -43.72
| RoleStore.GetByNames | p99 | 8ms | 5ms | -3ms | -37.95
| JobStore.GetAllByStatus | p99 | 8ms | 5ms | -3ms | -35.71
| UserStore.GetByUsername | p99 | 8ms | 6ms | -2ms | -26.24
| JobStore.GetNewestJobByStatusesAndType | p99 | 8ms | 6ms | -2ms | -25.97
| UserStore.Update | p99 | 20ms | 15ms | -5ms | -24.94
| UserStore.UpdateFailedPasswordAttempts | p99 | 12ms | 10ms | -2ms | -16.88
| StatusStore.UpdateExpiredDNDStatuses | p99 | 24ms | 21ms | -3ms | -12.61
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 22ms | -3ms | -12.12
| ChannelStore.CreateDirectChannel | p99 | 46ms | 42ms | -4ms | -8.61
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.401s | 2.294s | -107ms | -4.46
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 89ms | 86ms | -3ms | -3.36
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 5ms | 2ms | 70.19
| searchPostsInTeam | avg | 50ms | 74ms | 24ms | 48.37
| createGroupChannel | avg | 227ms | 247ms | 20ms | 8.81
| updateCategoriesForTeamForUser | avg | 49ms | 53ms | 4ms | 8.16
| getTeamStats | avg | 110ms | 114ms | 4ms | 3.64
| addTeamMember | avg | 686ms | 703ms | 17ms | 2.48
| searchAllChannels | avg | 954ms | 973ms | 19ms | 1.99
| createPost | avg | 242ms | 245ms | 3ms | 1.24
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 354ms | 1.368s | 1.014s | 286.22
| getChannelsForUser | p99 | 5ms | 12ms | 7ms | 140.42
| getChannel | p99 | 6ms | 14ms | 8ms | 126.48
| getChannelMembers | p99 | 5ms | 10ms | 5ms | 101.01
| deletePost | p99 | 25ms | 48ms | 23ms | 92.56
| addChannelMember | p99 | 249ms | 443ms | 194ms | 77.78
| getTeamsForUser | p99 | 5ms | 7ms | 2ms | 40.00
| getDrafts | p99 | 8ms | 11ms | 3ms | 38.83
| unfollowThreadByUser | p99 | 25ms | 33ms | 8ms | 32.19
| createGroupChannel | p99 | 495ms | 645ms | 150ms | 30.31
| createUser | p99 | 305ms | 344ms | 39ms | 12.80
| autocompleteUsers | p99 | 321ms | 350ms | 29ms | 9.04
| getPostsForChannel | p99 | 168ms | 183ms | 15ms | 8.93
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamScheduledPosts | avg | 4ms | 0s | -4ms | -111.51
| updateReadStateAllThreadsByUser | avg | 5ms | 0s | -5ms | -109.88
| getAnalytics | avg | 248ms | 0s | -248ms | -100.15
| createEmoji | avg | 2ms | 0s | -2ms | -80.21
| createChannelBookmark | avg | 24ms | 16ms | -8ms | -33.50
| createChannel | avg | 190ms | 154ms | -36ms | -18.97
| getPublicChannelsForTeam | avg | 11ms | 9ms | -2ms | -18.68
| createDirectChannel | avg | 152ms | 135ms | -17ms | -11.16
| autocompleteChannelsForTeamForSearch | avg | 221ms | 202ms | -19ms | -8.60
| getProfileImage | avg | 80ms | 74ms | -6ms | -7.49
| uploadFileStream | avg | 399ms | 370ms | -29ms | -7.27
| removeUserCustomStatus | avg | 94ms | 91ms | -3ms | -3.20
| addChannelMember | avg | 154ms | 152ms | -2ms | -1.30
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 10ms | 0s | -10ms | -101.52
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getTeamScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| createEmoji | p99 | 5ms | 0s | -5ms | -100.96
| getAnalytics | p99 | 371ms | 0s | -371ms | -99.90
| createChannelBookmark | p99 | 49ms | 25ms | -24ms | -49.23
| createChannel | p99 | 480ms | 249ms | -231ms | -48.12
| createDirectChannel | p99 | 463ms | 325ms | -138ms | -29.79
| patchPost | p99 | 70ms | 50ms | -20ms | -28.47
| getProfileImage | p99 | 360ms | 277ms | -83ms | -23.06
| getPublicChannelsForTeam | p99 | 25ms | 23ms | -2ms | -8.08
| autocompleteChannelsForTeamForSearch | p99 | 2.401s | 2.294s | -107ms | -4.46
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.455
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 13ms| 11ms | -2ms | -15.927
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 954ms| 972ms | 18ms | 1.888
| |  P99| 2.459s| 2.46s | 1ms | 0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 221ms| 202ms | -19ms | -8.601
| |  P99| 2.401s| 2.294s | -107ms | -4.456
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 46ms| 42ms | -4ms | -8.611
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.619
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.533
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 89ms| 86ms | -3ms | -3.355
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.780
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.723
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.064
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.017
| ChannelStore.GetMemberCount |  Avg| 70ms| 71ms | 1ms | 1.428
| |  P99| 246ms| 246ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.360
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 2ms| 4ms | 2ms | 80.550
| |  P99| 5ms| 10ms | 5ms | 101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.424
| ChannelStore.GetMembersForUserWithPagination |  Avg| 10ms| 11ms | 1ms | 9.718
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.521
| ChannelStore.GetPublicChannelsForTeam |  Avg| 10ms| 8ms | -2ms | -20.563
| |  P99| 25ms| 22ms | -3ms | -12.117
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.658
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 7ms | 1ms | 17.044
| |  P99| 18ms| 44ms | 26ms | 148.563
| ChannelStore.GetTeamChannels |  Avg| 24ms| 25ms | 1ms | 4.125
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.857
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.140
| ChannelStore.UpdateSidebarCategories |  Avg| 35ms| 36ms | 1ms | 2.898
| |  P99| 50ms| 88ms | 38ms | 76.382
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.117
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| CommandWebhookStore.Cleanup |  Avg| 3ms| 2ms | -1ms | -34.311
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.083
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.470
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 11ms | 4ms | 54.727
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.544
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -48.323
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.396
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.290
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.713
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 33ms| 9ms | -24ms | -73.282
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.974
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 8ms | -14ms | -64.665
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -28.137
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.872
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.461
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.271
| PostPersistentNotificationStore.Get |  Avg| 3ms| 2ms | -1ms | -36.202
| |  P99| 40ms| 5ms | -35ms | -88.050
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 742ms| 711ms | -31ms | -4.178
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.877
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.430
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.310
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.670
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 44ms| 68ms | 24ms | 55.044
| |  P99| 250ms| 1.368s | 1.118s | 447.456
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 40ms| 44ms | 4ms | 10.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 42.231
| |  P99| 5ms| 10ms | 5ms | 101.010
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.322
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.001
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.467
| ProductNoticesStore.View |  Avg| 34ms| 35ms | 1ms | 2.909
| |  P99| 92ms| 94ms | 2ms | 2.170
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 34.439
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.954
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 2ms | -1ms | -36.997
| |  P99| 21ms| 5ms | -16ms | -74.766
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.455
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.632
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.530
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.570
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.101
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.645
| StatusStore.SaveOrUpdate |  Avg| 9ms| 20ms | 11ms | 116.206
| |  P99| 196ms| 353ms | 157ms | 79.928
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.605
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 4ms | 1ms | 28.692
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 110ms| 114ms | 4ms | 3.641
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.003
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.638
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.020
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 82ms| 86ms | 4ms | 4.858
| |  P99| 100ms| 236ms | 136ms | 136.683
| TeamStore.SaveMember |  Avg| 70ms| 71ms | 1ms | 1.419
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.137
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.641
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.885
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -90.528
| |  P99| 10ms| 0s | -10ms | -101.523
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 4ms| 2ms | -2ms | -46.254
| |  P99| 10ms| 5ms | -5ms | -51.020
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 167ms| 168ms | 1ms | 0.598
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 143ms| 144ms | 1ms | 0.699
| |  P99| 362ms| 383ms | 21ms | 5.795
| UserStore.Count |  Avg| 53ms| 59ms | 6ms | 11.219
| |  P99| 99ms| 216ms | 117ms | 118.011
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.892
| UserStore.GetAllProfilesInChannel |  Avg| 249ms| 260ms | 11ms | 4.417
| |  P99| 497ms| 498ms | 1ms | 0.201
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.238
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.284
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -73.101
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.071
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 71ms | 1ms | 1.431
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 243ms| 243ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 15ms | -5ms | -24.938
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.878
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 154ms| 152ms | -2ms | -1.298
| | P99| 249ms| 443ms | 194ms | 77.778
| addTeamMember | Avg| 686ms| 703ms | 17ms | 2.479
| | P99| 2.378s| 2.391s | 13ms | 0.547
| autocompleteChannelsForTeamForSearch | Avg| 221ms| 202ms | -19ms | -8.599
| | P99| 2.401s| 2.294s | -107ms | -4.456
| autocompleteUsers | Avg| 124ms| 125ms | 1ms | 0.806
| | P99| 321ms| 350ms | 29ms | 9.043
| createChannel | Avg| 190ms| 154ms | -36ms | -18.969
| | P99| 480ms| 249ms | -231ms | -48.124
| createChannelBookmark | Avg| 24ms| 16ms | -8ms | -33.504
| | P99| 49ms| 25ms | -24ms | -49.231
| createDirectChannel | Avg| 152ms| 135ms | -17ms | -11.164
| | P99| 463ms| 325ms | -138ms | -29.789
| createEmoji | Avg| 2ms| 0s | -2ms | -80.211
| | P99| 5ms| 0s | -5ms | -100.959
| createGroupChannel | Avg| 227ms| 247ms | 20ms | 8.808
| | P99| 495ms| 645ms | 150ms | 30.315
| createPost | Avg| 242ms| 245ms | 3ms | 1.238
| | P99| 961ms| 961ms | 0s | 0.000
| createUser | Avg| 126ms| 127ms | 1ms | 0.794
| | P99| 305ms| 344ms | 39ms | 12.796
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.555
| followThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAnalytics | Avg| 248ms| 0s | -248ms | -100.150
| | P99| 371ms| 0s | -371ms | -99.896
| getCategoriesForTeamForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 6ms| 14ms | 8ms | 126.482
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getChannelMembers | Avg| 3ms| 5ms | 2ms | 70.190
| | P99| 5ms| 10ms | 5ms | 101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelMembersForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 223ms| 223ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 18.761
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 12ms | 7ms | 140.419
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 3ms | 1ms | 41.573
| | P99| 8ms| 11ms | 3ms | 38.827
| getFilePreview | Avg| 38ms| 37ms | -1ms | -2.664
| | P99| 95ms| 94ms | -1ms | -1.056
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 86ms| 85ms | -1ms | -1.166
| getFilteredUsersStats | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 20ms| 21ms | 1ms | 4.961
| | P99| 168ms| 183ms | 15ms | 8.934
| getPostsForChannelAroundLastUnread | Avg| 19ms| 20ms | 1ms | 5.169
| | P99| 50ms| 50ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -100.093
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 80ms| 74ms | -6ms | -7.491
| | P99| 360ms| 277ms | -83ms | -23.065
| getPublicChannelsForTeam | Avg| 11ms| 9ms | -2ms | -18.677
| | P99| 25ms| 23ms | -2ms | -8.076
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 2ms | -1ms | -39.999
| | P99| 7ms| 6ms | -1ms | -14.368
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 0s | -4ms | -111.512
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamStats | Avg| 110ms| 114ms | 4ms | 3.637
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.001
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 15ms| 14ms | -1ms | -6.668
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByGroupChannelIds | Avg| 4ms| 3ms | -1ms | -28.147
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| login | Avg| 66ms| 67ms | 1ms | 1.516
| | P99| 245ms| 246ms | 1ms | 0.409
| logout | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 70ms| 50ms | -20ms | -28.470
| removeUserCustomStatus | Avg| 94ms| 91ms | -3ms | -3.202
| | P99| 247ms| 246ms | -1ms | -0.405
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| searchAllChannels | Avg| 954ms| 973ms | 19ms | 1.992
| | P99| 2.459s| 2.46s | 1ms | 0.041
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.700
| searchPostsInTeam | Avg| 50ms| 74ms | 24ms | 48.375
| | P99| 354ms| 1.368s | 1.014s | 286.219
| searchUsers | Avg| 67ms| 67ms | 0s | 0.000
| | P99| 243ms| 243ms | 0s | 0.000
| setPostReminder | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 33ms | 8ms | 32.193
| updateCategoriesForTeamForUser | Avg| 49ms| 53ms | 4ms | 8.158
| | P99| 98ms| 99ms | 1ms | 1.018
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 5ms| 0s | -5ms | -109.882
| | P99| 10ms| 0s | -10ms | -101.523
| updateReadStateThreadByUser | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 399ms| 370ms | -29ms | -7.272
| | P99| 987ms| 982ms | -5ms | -0.506
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 30ms| 31ms | 1ms | 3.285
