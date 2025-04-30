### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 314ms | 313ms | 28357.41
| CommandWebhookStore.Cleanup | avg | 2ms | 5ms | 3ms | 143.36
| StatusStore.SaveOrUpdate | avg | 4ms | 10ms | 6ms | 143.02
| PostStore.SearchPostsForUser | avg | 60ms | 96ms | 36ms | 59.65
| ChannelStore.AnalyticsCountAll | avg | 84ms | 108ms | 24ms | 28.47
| ChannelStore.CreateSidebarCategory | avg | 22ms | 26ms | 4ms | 18.11
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 12ms | 14ms | 2ms | 16.22
| ChannelStore.UpdateSidebarCategories | avg | 39ms | 44ms | 5ms | 12.80
| UserStore.AutocompleteUsersInChannel | avg | 131ms | 135ms | 4ms | 3.05
| TeamStore.GetTotalMemberCount | avg | 78ms | 80ms | 2ms | 2.58
| UserStore.GetAllProfilesInChannel | avg | 197ms | 202ms | 5ms | 2.54
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9893.45
| StatusStore.SaveOrUpdate | p99 | 10ms | 115ms | 105ms | 1068.19
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 25ms | 20ms | 400.04
| PostStore.SearchPostsForUser | p99 | 475ms | 2.14s | 1.665s | 350.53
| ChannelStore.GetMembersForUserWithPagination | p99 | 10ms | 23ms | 13ms | 130.65
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 19ms | 10ms | 107.17
| CommandWebhookStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.95
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 50ms | 25ms | 100.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 49ms | 96ms | 47ms | 95.45
| UserStore.Update | p99 | 10ms | 19ms | 9ms | 90.45
| ReactionStore.GetForPost | p99 | 5ms | 9ms | 4ms | 80.50
| ChannelStore.GetPublicChannelsForTeam | p99 | 14ms | 23ms | 9ms | 64.19
| UserStore.GetForLogin | p99 | 5ms | 7ms | 2ms | 40.00
| ChannelStore.GetMember | p99 | 9ms | 12ms | 3ms | 33.47
| UserStore.Get | p99 | 6ms | 8ms | 2ms | 32.29
| ChannelStore.SaveMember | p99 | 51ms | 66ms | 15ms | 29.21
| UserStore.GetAllProfiles | p99 | 7ms | 9ms | 2ms | 28.86
| UserStore.UpdateUpdateAt | p99 | 14ms | 18ms | 4ms | 28.26
| ChannelStore.UpdateLastViewedAt | p99 | 12ms | 15ms | 3ms | 24.29
| FileInfoStore.AttachToPost | p99 | 14ms | 17ms | 3ms | 22.02
| PluginStore.Delete | p99 | 10ms | 12ms | 2ms | 20.39
| PostStore.Update | p99 | 33ms | 39ms | 6ms | 18.18
| UserStore.UpdateLastLogin | p99 | 12ms | 14ms | 2ms | 16.98
| ChannelStore.GetByName | p99 | 18ms | 21ms | 3ms | 16.26
| WebhookStore.GetOutgoingByTeam | p99 | 14ms | 16ms | 2ms | 13.96
| SessionStore.Get | p99 | 20ms | 22ms | 2ms | 9.89
| UserStore.Save | p99 | 129ms | 141ms | 12ms | 9.29
| ChannelStore.UpdateSidebarCategories | p99 | 221ms | 239ms | 18ms | 8.13
| UserStore.AutocompleteUsersInChannel | p99 | 358ms | 369ms | 11ms | 3.08
| ProductNoticesStore.View | p99 | 92ms | 94ms | 2ms | 2.18
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.343s | 2.375s | 32ms | 1.37
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SystemStore.PermanentDeleteByName | avg | 4ms | 0s | -4ms | -106.17
| SystemStore.SaveOrUpdate | avg | 4ms | 0s | -4ms | -104.54
| RetentionPolicyStore.GetAll | avg | 26ms | 0s | -26ms | -101.11
| PostStore.AnalyticsPostCountByTeam | avg | 2.991s | 504ms | -2.487s | -83.14
| PostStore.GetPostReminders | avg | 9ms | 7ms | -2ms | -21.93
| ChannelStore.AutocompleteInTeamForSearch | avg | 268ms | 243ms | -25ms | -9.33
| UserStore.Count | avg | 74ms | 68ms | -6ms | -8.12
| UserStore.AnalyticsActiveCount | avg | 127ms | 123ms | -4ms | -3.14
| TeamStore.GetActiveMemberCount | avg | 99ms | 96ms | -3ms | -3.04
| ChannelStore.Autocomplete | avg | 978ms | 963ms | -15ms | -1.53
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 50ms | 0s | -50ms | -100.50
| PostStore.AnalyticsPostCountByTeam | p99 | 10s | 985ms | -9.015s | -90.15
| ChannelStore.GetPinnedPostCount | p99 | 13ms | 5ms | -8ms | -63.56
| ChannelStore.CreateDirectChannel | p99 | 56ms | 25ms | -31ms | -55.85
| JobStore.Save | p99 | 19ms | 9ms | -10ms | -53.91
| SessionStore.Remove | p99 | 10ms | 5ms | -5ms | -50.76
| JobStore.GetCountByStatusAndType | p99 | 9ms | 5ms | -4ms | -46.51
| UserStore.GetUnreadCount | p99 | 13ms | 9ms | -4ms | -29.89
| UserStore.Count | p99 | 245ms | 242ms | -3ms | -1.23
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 63ms | 99ms | 36ms | 57.03
| logout | avg | 21ms | 32ms | 11ms | 52.53
| createCategoryForTeamForUser | avg | 23ms | 29ms | 6ms | 26.05
| createDirectChannel | avg | 146ms | 154ms | 8ms | 5.49
| createGroupChannel | avg | 218ms | 228ms | 10ms | 4.58
| autocompleteUsers | avg | 110ms | 115ms | 5ms | 4.53
| uploadFileStream | avg | 416ms | 433ms | 17ms | 4.09
| searchUsers | avg | 58ms | 60ms | 2ms | 3.44
| addTeamMember | avg | 674ms | 694ms | 20ms | 2.97
| createUser | avg | 110ms | 112ms | 2ms | 1.82
| createPost | avg | 164ms | 166ms | 2ms | 1.22
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 485ms | 2.14s | 1.655s | 341.24
| logout | p99 | 25ms | 97ms | 72ms | 289.74
| createCategoryForTeamForUser | p99 | 25ms | 50ms | 25ms | 100.60
| getProfileImage | p99 | 323ms | 418ms | 95ms | 29.40
| addChannelMember | p99 | 248ms | 300ms | 52ms | 20.95
| getPublicChannelsForTeam | p99 | 21ms | 23ms | 2ms | 9.37
| autocompleteUsers | p99 | 304ms | 325ms | 21ms | 6.90
| addTeamMember | p99 | 2.179s | 2.288s | 109ms | 5.00
| getPostsForChannel | p99 | 79ms | 82ms | 3ms | 3.82
| updateCategoriesForTeamForUser | p99 | 221ms | 229ms | 8ms | 3.61
| getFileThumbnail | p99 | 87ms | 89ms | 2ms | 2.29
| autocompleteChannelsForTeamForSearch | p99 | 2.343s | 2.375s | 32ms | 1.37
| createPost | p99 | 880ms | 891ms | 11ms | 1.25
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | avg | 3ms | 0s | -3ms | -117.33
| getAnalytics | avg | 1.373s | 265ms | -1.108s | -80.69
| getFilteredUsersStats | avg | 48ms | 21ms | -27ms | -55.87
| createChannel | avg | 187ms | 169ms | -18ms | -9.62
| autocompleteChannelsForTeamForSearch | avg | 268ms | 243ms | -25ms | -9.33
| removeUserCustomStatus | avg | 97ms | 95ms | -2ms | -2.06
| getTeamStats | avg | 99ms | 97ms | -2ms | -2.02
| searchAllChannels | avg | 978ms | 963ms | -15ms | -1.53
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -101.01
| getAnalytics | p99 | 10s | 985ms | -9.015s | -90.15
| getFilteredUsersStats | p99 | 99ms | 49ms | -50ms | -50.51
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.070
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -164.301
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 12ms| 11ms | -1ms | -8.417
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 84ms| 108ms | 24ms | 28.469
| |  P99| 248ms| 248ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 978ms| 963ms | -15ms | -1.534
| |  P99| 2.461s| 2.459s | -2ms | -0.081
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 268ms| 243ms | -25ms | -9.332
| |  P99| 2.343s| 2.375s | 32ms | 1.366
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 56ms| 25ms | -31ms | -55.853
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.063
| ChannelStore.CreateSidebarCategory |  Avg| 22ms| 26ms | 4ms | 18.115
| |  P99| 25ms| 50ms | 25ms | 100.604
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.709
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 14ms | 2ms | 16.223
| |  P99| 49ms| 96ms | 47ms | 95.449
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 21ms | 3ms | 16.259
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 6ms | 1ms | 18.512
| |  P99| 47ms| 48ms | 1ms | 2.105
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.131
| ChannelStore.GetMember |  Avg| 2ms| 3ms | 1ms | 41.220
| |  P99| 9ms| 12ms | 3ms | 33.468
| ChannelStore.GetMemberCount |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 245ms| 245ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 130.653
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -63.556
| ChannelStore.GetPublicChannelsForTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 14ms| 23ms | 9ms | 64.193
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 6.043
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 21ms| 22ms | 1ms | 4.813
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 3ms | 1ms | 40.705
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 51ms| 66ms | 15ms | 29.214
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.285
| ChannelStore.UpdateSidebarCategories |  Avg| 39ms| 44ms | 5ms | 12.802
| |  P99| 221ms| 239ms | 18ms | 8.127
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 107.168
| CommandWebhookStore.Cleanup |  Avg| 2ms| 5ms | 3ms | 143.362
| |  P99| 5ms| 10ms | 5ms | 100.948
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 9ms| 10ms | 1ms | 11.713
| |  P99| 25ms| 25ms | 0s | 0.000
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
| EmojiStore.Search |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 22.019
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.367
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.020
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 82.400
| |  P99| 5ms| 25ms | 20ms | 400.040
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -21.180
| |  P99| 19ms| 9ms | -10ms | -53.908
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.299
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.568
| JobStore.UpdateStatusOptimistically |  Avg| 8ms| 9ms | 1ms | 12.138
| |  P99| 22ms| 23ms | 1ms | 4.592
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -195.935
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.385
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.741
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.932
| PostStore.AnalyticsPostCount |  Avg| 1ms| 314ms | 313ms | 28357.408
| |  P99| 5ms| 495ms | 490ms | 9893.450
| PostStore.AnalyticsPostCountByTeam |  Avg| 2.991s| 504ms | -2.487s | -83.145
| |  P99| 10s| 985ms | -9.015s | -90.150
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.789
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.081
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 9ms| 7ms | -2ms | -21.927
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 5ms| 6ms | 1ms | 18.348
| |  P99| 39ms| 40ms | 1ms | 2.576
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 60ms| 96ms | 36ms | 59.655
| |  P99| 475ms| 2.14s | 1.665s | 350.529
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 16ms| 17ms | 1ms | 6.133
| |  P99| 33ms| 39ms | 6ms | 18.182
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 46.215
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 11ms| 12ms | 1ms | 8.705
| |  P99| 40ms| 39ms | -1ms | -2.501
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 34ms| 35ms | 1ms | 2.922
| |  P99| 92ms| 94ms | 2ms | 2.180
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.498
| RetentionPolicyStore.GetAll |  Avg| 26ms| 0s | -26ms | -101.113
| |  P99| 50ms| 0s | -50ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.893
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 5ms| 4ms | -1ms | -20.758
| |  P99| 10ms| 5ms | -5ms | -50.761
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 10ms | 6ms | 143.019
| |  P99| 10ms| 115ms | 105ms | 1068.192
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 27ms| 28ms | 1ms | 3.636
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.909
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.PermanentDeleteByName |  Avg| 4ms| 0s | -4ms | -106.169
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 4ms| 0s | -4ms | -104.541
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 99ms| 96ms | -3ms | -3.037
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 2ms | 1ms | 67.483
| |  P99| 7ms| 8ms | 1ms | 14.357
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.179
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.045
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 78ms| 80ms | 2ms | 2.577
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.747
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.974
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 1ms| 1ms | 0s | 0.000
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
| |  P99| 21ms| 22ms | 1ms | 4.716
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.695
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 127ms| 123ms | -4ms | -3.144
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 131ms| 135ms | 4ms | 3.047
| |  P99| 358ms| 369ms | 11ms | 3.076
| UserStore.Count |  Avg| 74ms| 68ms | -6ms | -8.123
| |  P99| 245ms| 242ms | -3ms | -1.225
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.294
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 28.859
| UserStore.GetAllProfilesInChannel |  Avg| 197ms| 202ms | 5ms | 2.544
| |  P99| 495ms| 496ms | 1ms | 0.202
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.004
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.848
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 9ms | -4ms | -29.892
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 72ms| 72ms | 0s | 0.000
| |  P99| 129ms| 141ms | 12ms | 9.292
| UserStore.Search |  Avg| 57ms| 58ms | 1ms | 1.752
| |  P99| 242ms| 242ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 90.452
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 5ms | 1ms | 22.249
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.975
| UserStore.UpdateUpdateAt |  Avg| 4ms| 5ms | 1ms | 22.707
| |  P99| 14ms| 18ms | 4ms | 28.261
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.959
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 147ms| 148ms | 1ms | 0.681
| | P99| 248ms| 300ms | 52ms | 20.948
| addTeamMember | Avg| 674ms| 694ms | 20ms | 2.966
| | P99| 2.179s| 2.288s | 109ms | 5.001
| autocompleteChannelsForTeamForSearch | Avg| 268ms| 243ms | -25ms | -9.330
| | P99| 2.343s| 2.375s | 32ms | 1.366
| autocompleteEmojis | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 110ms| 115ms | 5ms | 4.529
| | P99| 304ms| 325ms | 21ms | 6.898
| createCategoryForTeamForUser | Avg| 23ms| 29ms | 6ms | 26.048
| | P99| 25ms| 50ms | 25ms | 100.604
| createChannel | Avg| 187ms| 169ms | -18ms | -9.619
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 146ms| 154ms | 8ms | 5.487
| | P99| 248ms| 248ms | 0s | 0.000
| createGroupChannel | Avg| 218ms| 228ms | 10ms | 4.584
| | P99| 491ms| 492ms | 1ms | 0.203
| createPost | Avg| 164ms| 166ms | 2ms | 1.219
| | P99| 880ms| 891ms | 11ms | 1.250
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 110ms| 112ms | 2ms | 1.818
| | P99| 248ms| 248ms | 0s | 0.000
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 20ms| 21ms | 1ms | 5.048
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getAnalytics | Avg| 1.373s| 265ms | -1.108s | -80.689
| | P99| 10s| 985ms | -9.015s | -90.150
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 18ms| 19ms | 1ms | 5.610
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.422
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 204ms| 203ms | -1ms | -0.491
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getChannelsForUser | Avg| 9ms| 10ms | 1ms | 10.940
| | P99| 224ms| 222ms | -2ms | -0.891
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 37ms| 38ms | 1ms | 2.678
| | P99| 96ms| 97ms | 1ms | 1.039
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 87ms| 89ms | 2ms | 2.291
| getFilteredUsersStats | Avg| 48ms| 21ms | -27ms | -55.871
| | P99| 99ms| 49ms | -50ms | -50.505
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getPostsForChannel | Avg| 11ms| 12ms | 1ms | 8.901
| | P99| 79ms| 82ms | 3ms | 3.816
| getPostsForChannelAroundLastUnread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 46ms| 47ms | 1ms | 2.172
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 11ms | 1ms | 10.022
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 81ms| 81ms | 0s | 0.000
| | P99| 323ms| 418ms | 95ms | 29.399
| getPublicChannelsForTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.372
| getRolesByNames | Avg| 0s| 1ms | 1ms | 261.663
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 3ms | 1ms | 40.336
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 12ms | 1ms | 8.829
| getTeamScheduledPosts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.250
| getTeamStats | Avg| 99ms| 97ms | -2ms | -2.017
| | P99| 100ms| 100ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.039
| getTeamsUnreadForUser | Avg| 2ms| 3ms | 1ms | 40.928
| | P99| 12ms| 13ms | 1ms | 8.613
| getThreadsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 15ms | 1ms | 7.082
| getUsersByGroupChannelIds | Avg| 3ms| 0s | -3ms | -117.328
| | P99| 5ms| 0s | -5ms | -101.010
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 59ms| 60ms | 1ms | 1.688
| | P99| 245ms| 245ms | 0s | 0.000
| logout | Avg| 21ms| 32ms | 11ms | 52.535
| | P99| 25ms| 97ms | 72ms | 289.738
| patchPost | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.100
| removeUserCustomStatus | Avg| 97ms| 95ms | -2ms | -2.064
| | P99| 246ms| 246ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| searchAllChannels | Avg| 978ms| 963ms | -15ms | -1.534
| | P99| 2.461s| 2.459s | -2ms | -0.081
| searchGroupChannels | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 63ms| 99ms | 36ms | 57.030
| | P99| 485ms| 2.14s | 1.655s | 341.239
| searchUsers | Avg| 58ms| 60ms | 2ms | 3.443
| | P99| 242ms| 243ms | 1ms | 0.413
| setPostReminder | Avg| 13ms| 14ms | 1ms | 7.643
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 9.828
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 51ms| 50ms | -1ms | -1.977
| | P99| 221ms| 229ms | 8ms | 3.612
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 15ms| 16ms | 1ms | 6.506
| | P99| 25ms| 25ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 416ms| 433ms | 17ms | 4.091
| | P99| 989ms| 991ms | 2ms | 0.202
| upsertDraft | Avg| 4ms| 5ms | 1ms | 22.455
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
