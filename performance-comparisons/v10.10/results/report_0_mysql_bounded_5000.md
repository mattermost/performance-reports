### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 3ms | 389ms | 386ms | 13398.82
| StatusStore.SaveOrUpdate | avg | 4ms | 10ms | 6ms | 156.55
| PostStore.SearchPostsForUser | avg | 69ms | 101ms | 32ms | 46.25
| UserStore.Count | avg | 57ms | 75ms | 18ms | 31.83
| ChannelStore.Save | avg | 12ms | 15ms | 3ms | 24.58
| ChannelStore.AutocompleteInTeamForSearch | avg | 238ms | 261ms | 23ms | 9.65
| UserStore.AnalyticsActiveCount | avg | 121ms | 128ms | 7ms | 5.77
| UserStore.GetAllProfilesInChannel | avg | 195ms | 202ms | 7ms | 3.60
| PostStore.AnalyticsPostCountByTeam | avg | 472ms | 484ms | 12ms | 2.54
| ChannelStore.AnalyticsCountAll | avg | 138ms | 141ms | 3ms | 2.18
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 990ms | 985ms | 19897.39
| StatusStore.SaveOrUpdate | p99 | 10ms | 153ms | 143ms | 1504.57
| UserStore.Count | p99 | 99ms | 228ms | 129ms | 129.95
| PostStore.SearchPostsForUser | p99 | 1.356s | 2.858s | 1.502s | 110.78
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 21ms | 11ms | 110.55
| ChannelStore.GetSidebarCategory | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.GetUnreadCount | p99 | 19ms | 38ms | 19ms | 100.40
| SessionStore.Remove | p99 | 5ms | 9ms | 4ms | 80.81
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.Save | p99 | 10ms | 13ms | 3ms | 30.43
| PreferenceStore.GetAll | p99 | 10ms | 13ms | 3ms | 30.04
| UserTermsOfServiceStore.GetByUser | p99 | 7ms | 9ms | 2ms | 27.17
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 11ms | 13ms | 2ms | 18.34
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 78ms | 92ms | 14ms | 18.00
| ChannelStore.Save | p99 | 44ms | 48ms | 4ms | 9.09
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.267s | 2.417s | 150ms | 6.62
| ChannelStore.SaveMember | p99 | 50ms | 53ms | 3ms | 6.01
| UserStore.AutocompleteUsersInChannel | p99 | 361ms | 382ms | 21ms | 5.82
| ChannelStore.CreateDirectChannel | p99 | 44ms | 46ms | 2ms | 4.54
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -106.69
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 3ms | 0s | -3ms | -94.60
| PropertyFieldStore.SearchPropertyFields | avg | 2ms | 0s | -2ms | -85.45
| TokenStore.Cleanup | avg | 6ms | 2ms | -4ms | -70.76
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 13ms | 7ms | -6ms | -46.30
| ChannelStore.GetTeamChannels | avg | 40ms | 28ms | -12ms | -30.07
| ChannelBookmarkStore.Save | avg | 13ms | 10ms | -3ms | -23.95
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 9ms | 7ms | -2ms | -21.79
| ChannelStore.UpdateSidebarCategories | avg | 37ms | 31ms | -6ms | -16.02
| ProductNoticesStore.View | avg | 33ms | 30ms | -3ms | -9.09
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PropertyFieldStore.SearchPropertyFields | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetCountByStatusAndType | p99 | 36ms | 5ms | -31ms | -87.32
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 48ms | 10ms | -38ms | -78.76
| ChannelStore.GetPublicChannelsForTeam | p99 | 33ms | 10ms | -23ms | -68.93
| FileInfoStore.SetContent | p99 | 21ms | 10ms | -11ms | -52.06
| TokenStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.51
| JobStore.UpdateStatus | p99 | 18ms | 9ms | -9ms | -49.32
| StatusStore.UpdateExpiredDNDStatuses | p99 | 23ms | 12ms | -11ms | -48.27
| ChannelStore.UpdateSidebarCategories | p99 | 94ms | 50ms | -44ms | -46.81
| LinkMetadataStore.Save | p99 | 9ms | 5ms | -4ms | -46.24
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -42.78
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 8ms | -4ms | -34.33
| JobStore.UpdateOptimistically | p99 | 9ms | 6ms | -3ms | -32.61
| StatusStore.Get | p99 | 7ms | 5ms | -2ms | -29.61
| UserStore.GetByUsername | p99 | 7ms | 5ms | -2ms | -28.27
| PreferenceStore.Save | p99 | 35ms | 27ms | -8ms | -22.55
| ProductNoticesStore.View | p99 | 89ms | 84ms | -5ms | -5.64
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createUser | avg | 101ms | 249ms | 148ms | 146.18
| getRolesByNames | avg | 2ms | 4ms | 2ms | 101.36
| searchPostsInTeam | avg | 75ms | 106ms | 31ms | 41.42
| createChannel | avg | 168ms | 210ms | 42ms | 25.02
| autocompleteChannelsForTeamForSearch | avg | 238ms | 261ms | 23ms | 9.65
| createGroupChannel | avg | 203ms | 222ms | 19ms | 9.36
| autocompleteUsers | avg | 105ms | 111ms | 6ms | 5.72
| addTeamMember | avg | 646ms | 660ms | 14ms | 2.17
| getAnalytics | avg | 556ms | 567ms | 11ms | 1.98
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 100ms | 244ms | 144ms | 144.72
| searchPostsInTeam | p99 | 1.356s | 2.858s | 1.502s | 110.78
| createUser | p99 | 246ms | 494ms | 248ms | 100.82
| createChannelBookmark | p99 | 25ms | 48ms | 23ms | 92.56
| getUser | p99 | 10ms | 13ms | 3ms | 30.16
| getPreferences | p99 | 10ms | 13ms | 3ms | 28.61
| addTeamMember | p99 | 1.818s | 2.178s | 360ms | 19.80
| autocompleteUsers | p99 | 288ms | 338ms | 50ms | 17.37
| autocompleteChannelsForTeamForSearch | p99 | 2.267s | 2.417s | 150ms | 6.62
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroups | avg | 2ms | 0s | -2ms | -89.83
| getFilteredUsersStats | avg | 77ms | 43ms | -34ms | -44.29
| removeUserCustomStatus | avg | 102ms | 84ms | -18ms | -17.72
| createChannelBookmark | avg | 19ms | 16ms | -3ms | -15.97
| updateCategoriesForTeamForUser | avg | 47ms | 41ms | -6ms | -12.64
| getProfileImage | avg | 96ms | 89ms | -7ms | -7.28
| addChannelMember | avg | 157ms | 147ms | -10ms | -6.35
| uploadFileStream | avg | 432ms | 420ms | -12ms | -2.78
| createPost | avg | 153ms | 150ms | -3ms | -1.97
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| updateCategoriesForTeamForUser | p99 | 234ms | 50ms | -184ms | -78.80
| getPublicChannelsForTeam | p99 | 33ms | 10ms | -23ms | -68.93
| deletePost | p99 | 49ms | 25ms | -24ms | -49.23
| getDrafts | p99 | 8ms | 5ms | -3ms | -39.43
| getJobsByType | p99 | 8ms | 5ms | -3ms | -35.93
| getProfileImage | p99 | 451ms | 428ms | -23ms | -5.10
| createPost | p99 | 803ms | 766ms | -37ms | -4.61
| getPostsForChannel | p99 | 112ms | 108ms | -4ms | -3.56
| getFileThumbnail | p99 | 86ms | 84ms | -2ms | -2.32
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -106.691
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 13ms| 10ms | -3ms | -23.947
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.335
| ChannelStore.AnalyticsCountAll |  Avg| 138ms| 141ms | 3ms | 2.176
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 958ms| 965ms | 7ms | 0.731
| |  P99| 2.459s| 2.459s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 238ms| 261ms | 23ms | 9.649
| |  P99| 2.267s| 2.417s | 150ms | 6.616
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 44ms| 46ms | 2ms | 4.535
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.357
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 78ms| 92ms | 14ms | 17.997
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.291
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.863
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.155
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 63ms| 64ms | 1ms | 1.585
| |  P99| 245ms| 246ms | 1ms | 0.408
| ChannelStore.GetMemberForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 13ms| 7ms | -6ms | -46.302
| |  P99| 48ms| 10ms | -38ms | -78.756
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.931
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 33ms| 10ms | -23ms | -68.934
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| ChannelStore.GetTeamChannels |  Avg| 40ms| 28ms | -12ms | -30.065
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 12ms| 15ms | 3ms | 24.578
| |  P99| 44ms| 48ms | 4ms | 9.091
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 53ms | 3ms | 6.015
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 37ms| 31ms | -6ms | -16.016
| |  P99| 94ms| 50ms | -44ms | -46.808
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 8ms | -4ms | -34.335
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.441
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 9ms| 7ms | -2ms | -21.787
| |  P99| 25ms| 24ms | -1ms | -4.061
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.203
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 5ms | 1ms | 22.400
| |  P99| 10ms| 13ms | 3ms | 30.430
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -52.058
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.617
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -35.431
| |  P99| 36ms| 5ms | -31ms | -87.324
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.811
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 6ms | -3ms | -32.609
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -49.315
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 110.553
| LicenseStore.GetAll |  Avg| 2ms| 1ms | -1ms | -65.834
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.244
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.747
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 4ms | 1ms | 30.273
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.062
| PostPriorityStore.GetForPosts |  Avg| 2ms| 3ms | 1ms | 40.017
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 3ms| 389ms | 386ms | 13398.819
| |  P99| 5ms| 990ms | 985ms | 19897.387
| PostStore.AnalyticsPostCountByTeam |  Avg| 472ms| 484ms | 12ms | 2.542
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 16ms| 15ms | -1ms | -6.307
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.781
| PostStore.GetPostReminders |  Avg| 8ms| 7ms | -1ms | -12.472
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.491
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.105
| PostStore.SearchPostsForUser |  Avg| 69ms| 101ms | 32ms | 46.250
| |  P99| 1.356s| 2.858s | 1.502s | 110.775
| PostStore.SetPostReminder |  Avg| 8ms| 7ms | -1ms | -12.776
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.810
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.039
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 35ms| 27ms | -8ms | -22.550
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 30ms | -3ms | -9.085
| |  P99| 89ms| 84ms | -5ms | -5.640
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 0s | -2ms | -85.448
| |  P99| 5ms| 0s | -5ms | -101.010
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -82.839
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -120.631
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.393
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.609
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 10ms | 6ms | 156.549
| |  P99| 10ms| 153ms | 143ms | 1504.568
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 7ms | -1ms | -11.943
| |  P99| 23ms| 12ms | -11ms | -48.268
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.417
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 99ms| 98ms | -1ms | -1.012
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.066
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.968
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.194
| TeamStore.GetTotalMemberCount |  Avg| 76ms| 76ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.483
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 6ms| 2ms | -4ms | -70.759
| |  P99| 10ms| 5ms | -5ms | -50.505
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 121ms| 128ms | 7ms | 5.767
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 133ms| 133ms | 0s | 0.000
| |  P99| 361ms| 382ms | 21ms | 5.821
| UserStore.Count |  Avg| 57ms| 75ms | 18ms | 31.833
| |  P99| 99ms| 228ms | 129ms | 129.950
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.809
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.551
| UserStore.GetAllProfilesInChannel |  Avg| 195ms| 202ms | 7ms | 3.597
| |  P99| 495ms| 499ms | 4ms | 0.808
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.269
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 3ms| 0s | -3ms | -94.599
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 4ms | -1ms | -20.886
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 6ms | 1ms | 19.323
| |  P99| 19ms| 38ms | 19ms | 100.397
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 65ms| 66ms | 1ms | 1.533
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 57ms| 56ms | -1ms | -1.758
| |  P99| 242ms| 242ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.271
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.170
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 157ms| 147ms | -10ms | -6.353
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 646ms| 660ms | 14ms | 2.168
| | P99| 1.818s| 2.178s | 360ms | 19.800
| autocompleteChannelsForTeamForSearch | Avg| 238ms| 261ms | 23ms | 9.647
| | P99| 2.267s| 2.417s | 150ms | 6.616
| autocompleteUsers | Avg| 105ms| 111ms | 6ms | 5.721
| | P99| 288ms| 338ms | 50ms | 17.366
| createChannel | Avg| 168ms| 210ms | 42ms | 25.016
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 19ms| 16ms | -3ms | -15.974
| | P99| 25ms| 48ms | 23ms | 92.555
| createDirectChannel | Avg| 145ms| 146ms | 1ms | 0.689
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 203ms| 222ms | 19ms | 9.363
| | P99| 489ms| 492ms | 3ms | 0.614
| createPost | Avg| 153ms| 150ms | -3ms | -1.966
| | P99| 803ms| 766ms | -37ms | -4.610
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.213
| createUser | Avg| 101ms| 249ms | 148ms | 146.177
| | P99| 246ms| 494ms | 248ms | 100.817
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 23ms| 22ms | -1ms | -4.376
| | P99| 49ms| 25ms | -24ms | -49.231
| followThreadByUser | Avg| 13ms| 12ms | -1ms | -7.801
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 11ms | 1ms | 10.059
| getAnalytics | Avg| 556ms| 567ms | 11ms | 1.979
| | P99| 995ms| 995ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 14ms | 1ms | 7.769
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 206ms| 205ms | -1ms | -0.486
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.130
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -39.426
| getFilePreview | Avg| 38ms| 37ms | -1ms | -2.641
| | P99| 94ms| 93ms | -1ms | -1.064
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.165
| | P99| 86ms| 84ms | -2ms | -2.321
| getFilteredUsersStats | Avg| 77ms| 43ms | -34ms | -44.291
| | P99| 100ms| 99ms | -1ms | -1.005
| getGroups | Avg| 2ms| 0s | -2ms | -89.827
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 5ms | -3ms | -35.928
| getPostThread | Avg| 10ms| 11ms | 1ms | 9.634
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 112ms| 108ms | -4ms | -3.560
| getPostsForChannelAroundLastUnread | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 13ms | 3ms | 28.611
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 96ms| 89ms | -7ms | -7.279
| | P99| 451ms| 428ms | -23ms | -5.103
| getPublicChannelsForTeam | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 33ms| 10ms | -23ms | -68.934
| getRolesByNames | Avg| 2ms| 4ms | 2ms | 101.365
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 2ms | -1ms | -39.907
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 10ms | -1ms | -9.166
| getTeamScheduledPosts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getTeamStats | Avg| 99ms| 99ms | 0s | 0.000
| | P99| 100ms| 244ms | 144ms | 144.724
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.432
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUser | Avg| 2ms| 3ms | 1ms | 40.020
| | P99| 10ms| 13ms | 3ms | 30.157
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 12ms | 1ms | 9.278
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 57ms| 57ms | 0s | 0.000
| | P99| 242ms| 241ms | -1ms | -0.414
| logout | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| removeUserCustomStatus | Avg| 102ms| 84ms | -18ms | -17.716
| | P99| 247ms| 245ms | -2ms | -0.811
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| searchAllChannels | Avg| 958ms| 965ms | 7ms | 0.731
| | P99| 2.459s| 2.459s | 0s | 0.000
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 75ms| 106ms | 31ms | 41.416
| | P99| 1.356s| 2.858s | 1.502s | 110.775
| searchUsers | Avg| 58ms| 57ms | -1ms | -1.727
| | P99| 242ms| 242ms | 0s | 0.000
| setPostReminder | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 47ms| 41ms | -6ms | -12.639
| | P99| 234ms| 50ms | -184ms | -78.800
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 432ms| 420ms | -12ms | -2.779
| | P99| 994ms| 990ms | -4ms | -0.402
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
