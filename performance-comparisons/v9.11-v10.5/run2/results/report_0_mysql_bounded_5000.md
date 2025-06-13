### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Get | avg | 0s | 2ms | 2ms | 480.56
| ChannelStore.AutocompleteInTeamForSearch | avg | 76ms | 375ms | 299ms | 394.95
| UserStore.GetUnreadCount | avg | 2ms | 6ms | 4ms | 227.10
| JobStore.UpdateStatusOptimistically | avg | 4ms | 8ms | 4ms | 97.36
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 8ms | 11ms | 3ms | 36.69
| PostStore.SearchPostsForUser | avg | 69ms | 93ms | 24ms | 34.80
| ChannelStore.UpdateSidebarCategories | avg | 30ms | 34ms | 4ms | 13.24
| PostStore.AnalyticsPostCount | avg | 596ms | 625ms | 29ms | 4.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 248ms | 4.387s | 4.139s | 1668.80
| JobStore.UpdateStatus | p99 | 5ms | 18ms | 13ms | 262.63
| TeamStore.GetActiveMemberCount | p99 | 100ms | 244ms | 144ms | 144.72
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 18ms | 9ms | 101.98
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 24ms | 46ms | 22ms | 91.00
| UserStore.Update | p99 | 10ms | 19ms | 9ms | 90.51
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 93ms | 43ms | 86.43
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 9ms | 4ms | 80.81
| LinkMetadataStore.Save | p99 | 5ms | 8ms | 3ms | 60.61
| ClusterDiscoveryStore.SetLastPingAt | p99 | 6ms | 9ms | 3ms | 54.05
| ThreadStore.GetThreadForUser | p99 | 6ms | 9ms | 3ms | 47.89
| TeamStore.GetMember | p99 | 5ms | 7ms | 2ms | 40.29
| FileInfoStore.GetByIds | p99 | 5ms | 7ms | 2ms | 40.20
| PostStore.SearchPostsForUser | p99 | 1.585s | 2.18s | 595ms | 37.54
| ChannelStore.GetByName | p99 | 13ms | 17ms | 4ms | 30.48
| WebhookStore.GetOutgoingByTeam | p99 | 8ms | 10ms | 2ms | 25.13
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 12ms | 15ms | 3ms | 24.46
| ThreadStore.MaintainMembership | p99 | 17ms | 19ms | 2ms | 11.55
| ProductNoticesStore.View | p99 | 86ms | 91ms | 5ms | 5.79
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 6ms | 0s | -6ms | -94.39
| ChannelStore.GetAllChannelMembersForUser | avg | 5ms | 2ms | -3ms | -58.89
| ChannelStore.GetSidebarCategory | avg | 4ms | 2ms | -2ms | -45.13
| StatusStore.SaveOrUpdate | avg | 13ms | 8ms | -5ms | -38.90
| ChannelStore.GetMemberCount | avg | 80ms | 61ms | -19ms | -23.76
| UserStore.GetAllProfilesInChannel | avg | 251ms | 194ms | -57ms | -22.66
| UserStore.Count | avg | 58ms | 55ms | -3ms | -5.19
| ChannelStore.Autocomplete | avg | 954ms | 939ms | -15ms | -1.57
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 23ms | 0s | -23ms | -101.91
| JobStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetAllChannelMembersForUser | p99 | 29ms | 9ms | -20ms | -68.64
| ChannelStore.GetSidebarCategory | p99 | 10ms | 5ms | -5ms | -50.55
| PostStore.Update | p99 | 44ms | 25ms | -19ms | -43.26
| UserStore.GetByUsername | p99 | 10ms | 6ms | -4ms | -39.41
| FileInfoStore.AttachToPost | p99 | 15ms | 10ms | -5ms | -32.83
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 91ms | 66ms | -25ms | -27.39
| UserStore.GetForLogin | p99 | 7ms | 5ms | -2ms | -26.81
| ReactionStore.GetForPost | p99 | 8ms | 6ms | -2ms | -26.59
| UserStore.GetUnreadCount | p99 | 12ms | 9ms | -3ms | -26.06
| UserStore.GetAllProfiles | p99 | 9ms | 7ms | -2ms | -22.14
| StatusStore.SaveOrUpdate | p99 | 211ms | 170ms | -41ms | -19.44
| PreferenceStore.GetAll | p99 | 11ms | 9ms | -2ms | -18.72
| UserStore.UpdateUpdateAt | p99 | 16ms | 13ms | -3ms | -18.70
| UserStore.UpdateLastLogin | p99 | 15ms | 13ms | -2ms | -13.36
| UserStore.AutocompleteUsersInChannel | p99 | 363ms | 320ms | -43ms | -11.83
| SessionStore.Get | p99 | 20ms | 18ms | -2ms | -10.20
| SessionStore.Save | p99 | 20ms | 18ms | -2ms | -10.08
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 21ms | 19ms | -2ms | -9.73
| StatusStore.UpdateExpiredDNDStatuses | p99 | 24ms | 22ms | -2ms | -8.43
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 76ms | 376ms | 300ms | 395.95
| getPostThread | avg | 5ms | 7ms | 2ms | 42.84
| searchPostsInTeam | avg | 72ms | 97ms | 25ms | 34.62
| getProfileImage | avg | 95ms | 109ms | 14ms | 14.79
| uploadFileStream | avg | 450ms | 490ms | 40ms | 8.88
| autocompleteUsers | avg | 102ms | 105ms | 3ms | 2.94
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 248ms | 4.387s | 4.139s | 1668.80
| updateCategoriesForTeamForUser | p99 | 50ms | 93ms | 43ms | 86.43
| searchPostsInTeam | p99 | 1.585s | 2.18s | 595ms | 37.54
| getProfileImage | p99 | 455ms | 492ms | 37ms | 8.13
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | avg | 5ms | 3ms | -2ms | -40.63
| createPost | avg | 254ms | 153ms | -101ms | -39.72
| logout | avg | 27ms | 19ms | -8ms | -29.92
| patchPost | avg | 29ms | 21ms | -8ms | -27.27
| getChannelStats | avg | 8ms | 6ms | -2ms | -24.46
| createGroupChannel | avg | 250ms | 194ms | -56ms | -22.44
| login | avg | 68ms | 56ms | -12ms | -17.69
| removeUserCustomStatus | avg | 113ms | 93ms | -20ms | -17.68
| createChannel | avg | 207ms | 172ms | -35ms | -16.92
| addTeamMember | avg | 770ms | 641ms | -129ms | -16.74
| updateReadStateThreadByUser | avg | 18ms | 15ms | -3ms | -16.60
| createDirectChannel | avg | 168ms | 145ms | -23ms | -13.69
| createUser | avg | 114ms | 105ms | -9ms | -7.90
| addChannelMember | avg | 153ms | 141ms | -12ms | -7.86
| updateCategoriesForTeamForUser | avg | 40ms | 38ms | -2ms | -4.96
| getTeamStats | avg | 100ms | 97ms | -3ms | -3.00
| searchAllChannels | avg | 955ms | 940ms | -15ms | -1.57
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 322ms | 45ms | -277ms | -85.90
| logout | p99 | 50ms | 25ms | -25ms | -50.25
| deletePost | p99 | 47ms | 25ms | -22ms | -46.56
| getTeamsUnreadForUser | p99 | 17ms | 13ms | -4ms | -23.58
| getPreferences | p99 | 11ms | 9ms | -2ms | -17.50
| getUsers | p99 | 12ms | 10ms | -2ms | -16.70
| autocompleteUsers | p99 | 319ms | 269ms | -50ms | -15.69
| addTeamMember | p99 | 2.372s | 2.022s | -350ms | -14.75
| createDirectChannel | p99 | 277ms | 248ms | -29ms | -10.45
| createPost | p99 | 921ms | 837ms | -84ms | -9.12
| getChannelStats | p99 | 216ms | 200ms | -16ms | -7.42
| updateReadStateThreadByUser | p99 | 28ms | 26ms | -2ms | -7.24
| createGroupChannel | p99 | 496ms | 480ms | -16ms | -3.23
| login | p99 | 250ms | 242ms | -8ms | -3.20
| getPostsForChannel | p99 | 81ms | 79ms | -2ms | -2.47
| removeUserCustomStatus | p99 | 248ms | 245ms | -3ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.931
| BotStore.Get |  Avg| 0s| 2ms | 2ms | 480.564
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.459
| ChannelStore.Autocomplete |  Avg| 954ms| 939ms | -15ms | -1.572
| |  P99| 2.466s| 2.459s | -7ms | -0.284
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 76ms| 375ms | 299ms | 394.954
| |  P99| 248ms| 4.387s | 4.139s | 1668.801
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 18ms | 1ms | 5.827
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 20ms| 19ms | -1ms | -5.110
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 6ms| 0s | -6ms | -94.393
| |  P99| 23ms| 0s | -23ms | -101.908
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 2ms | -3ms | -58.888
| |  P99| 29ms| 9ms | -20ms | -68.644
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 91ms| 66ms | -25ms | -27.390
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.480
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 80ms| 61ms | -19ms | -23.764
| |  P99| 247ms| 245ms | -2ms | -0.810
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 1ms| 2ms | 1ms | 71.021
| |  P99| 8ms| 9ms | 1ms | 12.846
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.316
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.734
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 2ms | -2ms | -45.126
| |  P99| 10ms| 5ms | -5ms | -50.551
| ChannelStore.GetTeamChannels |  Avg| 25ms| 24ms | -1ms | -4.068
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 8.700
| |  P99| 47ms| 48ms | 1ms | 2.121
| ChannelStore.SaveMember |  Avg| 21ms| 20ms | -1ms | -4.867
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 30ms| 34ms | 4ms | 13.241
| |  P99| 50ms| 93ms | 43ms | 86.432
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 4ms | 1ms | 28.596
| |  P99| 6ms| 9ms | 3ms | 54.054
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 11ms | 3ms | 36.690
| |  P99| 24ms| 46ms | 22ms | 91.002
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.675
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -32.832
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.197
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.616
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 85.851
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.331
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.072
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 8ms | 4ms | 97.355
| |  P99| 9ms| 18ms | 9ms | 101.983
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 29.113
| |  P99| 5ms| 8ms | 3ms | 60.606
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.120
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
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
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 596ms| 625ms | 29ms | 4.863
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.810
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.643
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 69ms| 93ms | 24ms | 34.798
| |  P99| 1.585s| 2.18s | 595ms | 37.542
| PostStore.SetPostReminder |  Avg| 8ms| 7ms | -1ms | -12.879
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 14ms | -1ms | -6.853
| |  P99| 44ms| 25ms | -19ms | -43.264
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.720
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 30ms| 31ms | 1ms | 3.357
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 2ms | -1ms | -39.871
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 31ms| 32ms | 1ms | 3.194
| |  P99| 86ms| 91ms | 5ms | 5.788
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.594
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 1ms | 1ms | 331492.979
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 3ms | -1ms | -28.119
| |  P99| 20ms| 18ms | -2ms | -10.198
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.046
| SessionStore.GetSessionsExpired |  Avg| 0s| 1ms | 1ms | 227.392
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.077
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 13ms| 8ms | -5ms | -38.903
| |  P99| 211ms| 170ms | -41ms | -19.437
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 7ms | -1ms | -12.819
| |  P99| 24ms| 22ms | -2ms | -8.430
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 97ms| 97ms | 0s | 0.000
| |  P99| 100ms| 244ms | 144ms | 144.724
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.291
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 76ms| 77ms | 1ms | 1.314
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.438
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 47.890
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.278
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 7ms | 1ms | 16.425
| |  P99| 17ms| 19ms | 2ms | 11.549
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.948
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 127ms| 127ms | 0s | 0.000
| |  P99| 363ms| 320ms | -43ms | -11.830
| UserStore.Count |  Avg| 58ms| 55ms | -3ms | -5.194
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 2ms | 1ms | 83.318
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.141
| UserStore.GetAllProfilesInChannel |  Avg| 251ms| 194ms | -57ms | -22.665
| |  P99| 499ms| 496ms | -3ms | -0.601
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 6ms | -4ms | -39.409
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -26.814
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.976
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 4ms | 1ms | 29.328
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 6ms | 4ms | 227.097
| |  P99| 12ms| 9ms | -3ms | -26.059
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 70ms | 1ms | 1.447
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 28ms| 29ms | 1ms | 3.539
| |  P99| 240ms| 242ms | 2ms | 0.832
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 90.505
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.359
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.704
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.128
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 153ms| 141ms | -12ms | -7.857
| | P99| 248ms| 248ms | 0s | 0.000
| addTeamMember | Avg| 770ms| 641ms | -129ms | -16.743
| | P99| 2.372s| 2.022s | -350ms | -14.753
| autocompleteChannelsForTeamForSearch | Avg| 76ms| 376ms | 300ms | 395.952
| | P99| 248ms| 4.387s | 4.139s | 1668.801
| autocompleteUsers | Avg| 102ms| 105ms | 3ms | 2.937
| | P99| 319ms| 269ms | -50ms | -15.691
| createChannel | Avg| 207ms| 172ms | -35ms | -16.922
| | P99| 249ms| 249ms | 0s | 0.000
| createDirectChannel | Avg| 168ms| 145ms | -23ms | -13.693
| | P99| 277ms| 248ms | -29ms | -10.453
| createGroupChannel | Avg| 250ms| 194ms | -56ms | -22.435
| | P99| 496ms| 480ms | -16ms | -3.229
| createPost | Avg| 254ms| 153ms | -101ms | -39.725
| | P99| 921ms| 837ms | -84ms | -9.119
| createUser | Avg| 114ms| 105ms | -9ms | -7.902
| | P99| 248ms| 247ms | -1ms | -0.403
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 19ms| 18ms | -1ms | -5.359
| | P99| 47ms| 25ms | -22ms | -46.562
| followThreadByUser | Avg| 10ms| 9ms | -1ms | -10.388
| | P99| 25ms| 24ms | -1ms | -4.073
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.513
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.582
| getChannel | Avg| 5ms| 3ms | -2ms | -40.626
| | P99| 10ms| 9ms | -1ms | -10.096
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForUser | Avg| 1ms| 2ms | 1ms | 66.705
| | P99| 8ms| 9ms | 1ms | 12.317
| getChannelStats | Avg| 8ms| 6ms | -2ms | -24.464
| | P99| 216ms| 200ms | -16ms | -7.417
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getDrafts | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 96ms| 95ms | -1ms | -1.045
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.174
| | P99| 89ms| 88ms | -1ms | -1.121
| getPostThread | Avg| 5ms| 7ms | 2ms | 42.839
| | P99| 10ms| 10ms | 0s | 0.000
| getPostsForChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 81ms| 79ms | -2ms | -2.468
| getPostsForChannelAroundLastUnread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 49ms| 48ms | -1ms | -2.057
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 9ms | -2ms | -17.499
| getProfileImage | Avg| 95ms| 109ms | 14ms | 14.785
| | P99| 455ms| 492ms | 37ms | 8.127
| getPublicChannelsForTeam | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.086
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.092
| getTeamStats | Avg| 100ms| 97ms | -3ms | -3.004
| | P99| 246ms| 244ms | -2ms | -0.815
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 3ms| 2ms | -1ms | -37.483
| | P99| 17ms| 13ms | -4ms | -23.578
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 10ms | -2ms | -16.703
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 68ms| 56ms | -12ms | -17.687
| | P99| 250ms| 242ms | -8ms | -3.202
| logout | Avg| 27ms| 19ms | -8ms | -29.923
| | P99| 50ms| 25ms | -25ms | -50.251
| patchPost | Avg| 29ms| 21ms | -8ms | -27.274
| | P99| 322ms| 45ms | -277ms | -85.903
| removeUserCustomStatus | Avg| 113ms| 93ms | -20ms | -17.681
| | P99| 248ms| 245ms | -3ms | -1.211
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| searchAllChannels | Avg| 955ms| 940ms | -15ms | -1.571
| | P99| 2.466s| 2.459s | -7ms | -0.284
| searchGroupChannels | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 72ms| 97ms | 25ms | 34.616
| | P99| 1.585s| 2.18s | 595ms | 37.542
| searchUsers | Avg| 29ms| 30ms | 1ms | 3.424
| | P99| 241ms| 242ms | 1ms | 0.414
| setPostReminder | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 10ms | 1ms | 10.744
| | P99| 24ms| 24ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 40ms| 38ms | -2ms | -4.960
| | P99| 50ms| 93ms | 43ms | 86.432
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 18ms| 15ms | -3ms | -16.604
| | P99| 28ms| 26ms | -2ms | -7.244
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 450ms| 490ms | 40ms | 8.881
| | P99| 998ms| 997ms | -1ms | -0.100
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 9ms| 10ms | 1ms | 11.495
| | P99| 25ms| 25ms | 0s | 0.000
