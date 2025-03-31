### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 3ms | 300ms | 297ms | 8919.19
| CommandWebhookStore.Cleanup | avg | 2ms | 10ms | 8ms | 358.53
| StatusStore.SaveOrUpdate | avg | 4ms | 13ms | 9ms | 213.85
| TokenStore.Cleanup | avg | 5ms | 10ms | 5ms | 91.37
| LinkMetadataStore.Save | avg | 2ms | 4ms | 2ms | 84.91
| ChannelStore.UpdateSidebarCategories | avg | 40ms | 46ms | 6ms | 14.82
| PostStore.Delete | avg | 15ms | 17ms | 2ms | 13.71
| PostStore.SearchPostsForUser | avg | 53ms | 60ms | 7ms | 13.09
| UserStore.GetAllProfilesInChannel | avg | 185ms | 191ms | 6ms | 3.25
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9890.78
| StatusStore.SaveOrUpdate | p99 | 10ms | 211ms | 201ms | 2050.26
| JobStore.GetCountByStatusAndType | p99 | 5ms | 76ms | 71ms | 1434.34
| CommandWebhookStore.Cleanup | p99 | 5ms | 25ms | 20ms | 403.70
| TokenStore.Cleanup | p99 | 10ms | 25ms | 15ms | 151.51
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.81
| PostPersistentNotificationStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| LinkMetadataStore.Save | p99 | 5ms | 9ms | 4ms | 80.53
| PostStore.Delete | p99 | 25ms | 45ms | 20ms | 80.48
| UserStore.Update | p99 | 10ms | 18ms | 8ms | 80.40
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 49ms | 85ms | 36ms | 72.77
| ChannelStore.GetChannelsByUser | p99 | 48ms | 82ms | 34ms | 71.39
| FileInfoStore.Save | p99 | 10ms | 14ms | 4ms | 40.26
| UserStore.GetUnreadCount | p99 | 18ms | 22ms | 4ms | 22.45
| UserStore.UpdateLastLogin | p99 | 14ms | 16ms | 2ms | 13.92
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.423s | 2.572s | 149ms | 6.15
| UserStore.AutocompleteUsersInChannel | p99 | 342ms | 360ms | 18ms | 5.26
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 22ms | 0s | -22ms | -101.29
| UserStore.AnalyticsActiveCount | avg | 132ms | 121ms | -11ms | -8.36
| ChannelStore.AutocompleteInTeamForSearch | avg | 275ms | 256ms | -19ms | -6.90
| PostStore.AnalyticsPostCountByTeam | avg | 498ms | 476ms | -22ms | -4.42
| ChannelStore.AnalyticsCountAll | avg | 141ms | 137ms | -4ms | -2.83
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetByName | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetSidebarCategory | p99 | 22ms | 10ms | -12ms | -54.55
| SessionStore.Remove | p99 | 10ms | 5ms | -5ms | -51.02
| PostStore.AnalyticsPostCountByTeam | p99 | 992ms | 498ms | -494ms | -49.77
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.24
| ChannelStore.CreateDirectChannel | p99 | 39ms | 25ms | -14ms | -35.44
| ChannelStore.Save | p99 | 38ms | 25ms | -13ms | -34.44
| ChannelStore.GetMember | p99 | 9ms | 7ms | -2ms | -21.79
| PreferenceStore.GetAll | p99 | 11ms | 9ms | -2ms | -18.78
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 10ms | -2ms | -17.17
| FileInfoStore.SetContent | p99 | 25ms | 21ms | -4ms | -16.17
| PostStore.Update | p99 | 44ms | 39ms | -5ms | -11.40
| PreferenceStore.Save | p99 | 35ms | 33ms | -2ms | -5.69
| ChannelStore.UpdateSidebarCategories | p99 | 233ms | 226ms | -7ms | -3.00
| ProductNoticesStore.View | p99 | 90ms | 88ms | -2ms | -2.23
| PostStore.SearchPostsForUser | p99 | 1.139s | 1.127s | -12ms | -1.05
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 18ms | 76ms | 58ms | 329.43
| createChannelBookmark | avg | 15ms | 18ms | 3ms | 19.46
| searchPostsInTeam | avg | 56ms | 63ms | 7ms | 12.39
| deletePost | avg | 20ms | 22ms | 2ms | 9.84
| updateCategoriesForTeamForUser | avg | 52ms | 54ms | 2ms | 3.83
| addTeamMember | avg | 623ms | 635ms | 12ms | 1.93
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | p99 | 25ms | 100ms | 75ms | 301.81
| deletePost | p99 | 25ms | 45ms | 20ms | 80.48
| addTeamMember | p99 | 999ms | 1.792s | 793ms | 79.37
| getPostThread | p99 | 10ms | 12ms | 2ms | 20.02
| getProfileImage | p99 | 331ms | 361ms | 30ms | 9.06
| autocompleteUsers | p99 | 297ms | 319ms | 22ms | 7.42
| autocompleteChannelsForTeamForSearch | p99 | 2.423s | 2.572s | 149ms | 6.15
| createPost | p99 | 786ms | 817ms | 31ms | 3.94
| getFileThumbnail | p99 | 86ms | 88ms | 2ms | 2.31
| getFilePreview | p99 | 98ms | 100ms | 2ms | 2.04
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | avg | 3ms | 0s | -3ms | -115.91
| getChannelByNameForTeamName | avg | 3ms | 0s | -3ms | -100.85
| createCategoryForTeamForUser | avg | 23ms | 0s | -23ms | -99.49
| getChannelsForUser | avg | 10ms | 8ms | -2ms | -20.09
| removeUserCustomStatus | avg | 99ms | 91ms | -8ms | -8.09
| patchPost | avg | 27ms | 25ms | -2ms | -7.40
| autocompleteChannelsForTeamForSearch | avg | 275ms | 256ms | -19ms | -6.90
| getAnalytics | avg | 571ms | 546ms | -25ms | -4.38
| createDirectChannel | avg | 153ms | 148ms | -5ms | -3.26
| createGroupChannel | avg | 220ms | 213ms | -7ms | -3.18
| getProfileImage | avg | 79ms | 77ms | -2ms | -2.54
| addChannelMember | avg | 152ms | 150ms | -2ms | -1.32
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getChannelByNameForTeamName | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| patchPost | p99 | 104ms | 49ms | -55ms | -52.63
| getPreferences | p99 | 12ms | 10ms | -2ms | -16.81
| getCategoriesForTeamForUser | p99 | 21ms | 19ms | -2ms | -9.68
| getPostsForChannel | p99 | 94ms | 86ms | -8ms | -8.52
| updateCategoriesForTeamForUser | p99 | 233ms | 227ms | -6ms | -2.57
| getChannelsForUser | p99 | 220ms | 217ms | -3ms | -1.36
| searchPostsInTeam | p99 | 1.139s | 1.127s | -12ms | -1.05
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 5ms | 1ms | 22.254
| |  P99| 20ms| 20ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -60.124
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -101.589
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.630
| ChannelStore.AnalyticsCountAll |  Avg| 141ms| 137ms | -4ms | -2.829
| |  P99| 249ms| 249ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 943ms| 941ms | -2ms | -0.212
| |  P99| 2.459s| 2.458s | -1ms | -0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 275ms| 256ms | -19ms | -6.902
| |  P99| 2.423s| 2.572s | 149ms | 6.150
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -35.443
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 22ms| 0s | -22ms | -101.290
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.599
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 14ms | 1ms | 7.500
| |  P99| 49ms| 85ms | 36ms | 72.768
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.190
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 82ms | 34ms | 71.391
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.493
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.792
| ChannelStore.GetMemberCount |  Avg| 61ms| 62ms | 1ms | 1.644
| |  P99| 245ms| 245ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.277
| ChannelStore.GetPublicChannelsForTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.943
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 5ms | -1ms | -18.155
| |  P99| 22ms| 10ms | -12ms | -54.546
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 12ms| 11ms | -1ms | -8.629
| |  P99| 38ms| 25ms | -13ms | -34.437
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.014
| ChannelStore.UpdateSidebarCategories |  Avg| 40ms| 46ms | 6ms | 14.825
| |  P99| 233ms| 226ms | -7ms | -2.998
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.167
| CommandWebhookStore.Cleanup |  Avg| 2ms| 10ms | 8ms | 358.527
| |  P99| 5ms| 25ms | 20ms | 403.705
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.730
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.265
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 21ms | -4ms | -16.168
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 95.996
| |  P99| 5ms| 76ms | 71ms | 1434.343
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 4ms | 2ms | 84.908
| |  P99| 5ms| 9ms | 4ms | 80.533
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.873
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.245
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 3ms| 300ms | 297ms | 8919.192
| |  P99| 5ms| 495ms | 490ms | 9890.779
| PostStore.AnalyticsPostCountByTeam |  Avg| 498ms| 476ms | -22ms | -4.415
| |  P99| 992ms| 498ms | -494ms | -49.773
| PostStore.Delete |  Avg| 15ms| 17ms | 2ms | 13.709
| |  P99| 25ms| 45ms | 20ms | 80.483
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.783
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 39ms | 1ms | 2.610
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 53ms| 60ms | 7ms | 13.093
| |  P99| 1.139s| 1.127s | -12ms | -1.054
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 44ms| 39ms | -5ms | -11.396
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 45.303
| |  P99| 5ms| 9ms | 4ms | 80.808
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.778
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 35ms| 33ms | -2ms | -5.688
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 34ms | 1ms | 2.987
| |  P99| 90ms| 88ms | -2ms | -2.225
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -123.748
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 5ms | 1ms | 24.757
| |  P99| 9ms| 10ms | 1ms | 10.989
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 5ms| 4ms | -1ms | -21.031
| |  P99| 10ms| 5ms | -5ms | -51.021
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.375
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 13ms | 9ms | 213.852
| |  P99| 10ms| 211ms | 201ms | 2050.259
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.515
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 1ms | -1ms | -64.889
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetByName |  Avg| 1ms| 0s | -1ms | -89.846
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.584
| TeamStore.SaveMember |  Avg| 69ms| 68ms | -1ms | -1.458
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.250
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.332
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 5ms| 10ms | 5ms | 91.366
| |  P99| 10ms| 25ms | 15ms | 151.514
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 132ms| 121ms | -11ms | -8.358
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 128ms| 128ms | 0s | 0.000
| |  P99| 342ms| 360ms | 18ms | 5.261
| UserStore.Count |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 185ms| 191ms | 6ms | 3.245
| |  P99| 494ms| 495ms | 1ms | 0.202
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 2ms| 3ms | 1ms | 42.541
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.455
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 56ms| 56ms | 0s | 0.000
| |  P99| 241ms| 241ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 80.402
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.917
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.250
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 152ms| 150ms | -2ms | -1.317
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 623ms| 635ms | 12ms | 1.926
| | P99| 999ms| 1.792s | 793ms | 79.373
| autocompleteChannelsForTeamForSearch | Avg| 275ms| 256ms | -19ms | -6.900
| | P99| 2.423s| 2.572s | 149ms | 6.150
| autocompleteUsers | Avg| 111ms| 111ms | 0s | 0.000
| | P99| 297ms| 319ms | 22ms | 7.417
| createCategoryForTeamForUser | Avg| 23ms| 0s | -23ms | -99.490
| | P99| 25ms| 0s | -25ms | -100.604
| createChannelBookmark | Avg| 15ms| 18ms | 3ms | 19.463
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 153ms| 148ms | -5ms | -3.262
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 220ms| 213ms | -7ms | -3.178
| | P99| 487ms| 487ms | 0s | 0.000
| createPost | Avg| 152ms| 152ms | 0s | 0.000
| | P99| 786ms| 817ms | 31ms | 3.944
| createSchedulePost | Avg| 4ms| 5ms | 1ms | 23.454
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 98ms| 98ms | 0s | 0.000
| | P99| 245ms| 245ms | 0s | 0.000
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 20ms| 22ms | 2ms | 9.844
| | P99| 25ms| 45ms | 20ms | 80.483
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getAnalytics | Avg| 571ms| 546ms | -25ms | -4.378
| | P99| 995ms| 995ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 5ms| 4ms | -1ms | -21.875
| | P99| 21ms| 19ms | -2ms | -9.679
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelByNameForTeamName | Avg| 3ms| 0s | -3ms | -100.854
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 204ms| 205ms | 1ms | 0.491
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelsForUser | Avg| 10ms| 8ms | -2ms | -20.090
| | P99| 220ms| 217ms | -3ms | -1.364
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 100ms | 2ms | 2.037
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 86ms| 88ms | 2ms | 2.314
| getFilteredUsersStats | Avg| 18ms| 76ms | 58ms | 329.428
| | P99| 25ms| 100ms | 75ms | 301.811
| getGroups | Avg| 2ms| 1ms | -1ms | -65.214
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 0s | -1ms | -79.489
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.021
| getPostsForChannel | Avg| 14ms| 13ms | -1ms | -7.317
| | P99| 94ms| 86ms | -8ms | -8.515
| getPostsForChannelAroundLastUnread | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 48ms| 47ms | -1ms | -2.097
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 12ms| 10ms | -2ms | -16.815
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 0s | -1ms | -84.691
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 79ms| 77ms | -2ms | -2.537
| | P99| 331ms| 361ms | 30ms | 9.061
| getPublicChannelsForTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| getRolesByNames | Avg| 1ms| 0s | -1ms | -133.657
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 10ms | -1ms | -9.158
| getTeamScheduledPosts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.330
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 10ms | -1ms | -8.766
| getUsersByGroupChannelIds | Avg| 3ms| 0s | -3ms | -115.913
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 56ms| 57ms | 1ms | 1.781
| | P99| 241ms| 241ms | 0s | 0.000
| logout | Avg| 21ms| 20ms | -1ms | -4.700
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 27ms| 25ms | -2ms | -7.395
| | P99| 104ms| 49ms | -55ms | -52.633
| removeUserCustomStatus | Avg| 99ms| 91ms | -8ms | -8.087
| | P99| 246ms| 246ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| searchAllChannels | Avg| 943ms| 941ms | -2ms | -0.212
| | P99| 2.459s| 2.458s | -1ms | -0.041
| searchGroupChannels | Avg| 1ms| 2ms | 1ms | 67.144
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 56ms| 63ms | 7ms | 12.392
| | P99| 1.139s| 1.127s | -12ms | -1.054
| searchUsers | Avg| 57ms| 56ms | -1ms | -1.756
| | P99| 241ms| 241ms | 0s | 0.000
| setPostReminder | Avg| 14ms| 13ms | -1ms | -6.926
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 52ms| 54ms | 2ms | 3.827
| | P99| 233ms| 227ms | -6ms | -2.570
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 26ms| 25ms | -1ms | -3.844
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 381ms| 380ms | -1ms | -0.262
| | P99| 992ms| 984ms | -8ms | -0.807
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
