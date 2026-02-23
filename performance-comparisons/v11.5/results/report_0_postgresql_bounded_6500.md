### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.GetPendingScheduledPosts | avg | 2ms | 6ms | 4ms | 218.98
| TokenStore.Cleanup | avg | 2ms | 6ms | 4ms | 180.93
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 2ms | 5ms | 3ms | 120.26
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 4ms | 2ms | 92.08
| UserStore.GetProfilesInChannel | avg | 10ms | 19ms | 9ms | 89.44
| PostStore.AnalyticsPostCount | avg | 135ms | 198ms | 63ms | 46.63
| ChannelStore.Autocomplete | avg | 33ms | 42ms | 9ms | 27.20
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 92ms | 87ms | 1757.58
| UserStore.GetProfilesInChannel | p99 | 25ms | 233ms | 208ms | 838.71
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 46ms | 41ms | 828.28
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 46ms | 41ms | 828.28
| PostStore.GetPostReminders | p99 | 10ms | 92ms | 82ms | 824.12
| TokenStore.Cleanup | p99 | 5ms | 25ms | 20ms | 403.90
| StatusStore.UpdateExpiredDNDStatuses | p99 | 6ms | 28ms | 22ms | 396.40
| BotStore.Get | p99 | 5ms | 23ms | 18ms | 363.64
| ChannelStore.Autocomplete | p99 | 99ms | 389ms | 290ms | 293.89
| UserStore.GetByUsername | p99 | 5ms | 17ms | 12ms | 242.42
| ChannelStore.Save | p99 | 25ms | 58ms | 33ms | 133.26
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 23ms | 13ms | 132.31
| JobStore.GetAllByStatus | p99 | 9ms | 17ms | 8ms | 90.70
| UserStore.Update | p99 | 10ms | 15ms | 5ms | 50.25
| StatusStore.SaveOrUpdateMany | p99 | 42ms | 58ms | 16ms | 37.87
| PostPriorityStore.GetForPost | p99 | 17ms | 23ms | 6ms | 35.29
| UserStore.IsEmpty | p99 | 10ms | 12ms | 2ms | 20.19
| GroupStore.GetGroups | p99 | 14ms | 16ms | 2ms | 13.84
| UserStore.GetProfileByIds | p99 | 19ms | 21ms | 2ms | 10.34
| UserStore.AutocompleteUsersInChannel | p99 | 164ms | 176ms | 12ms | 7.30
| ChannelStore.CreateInitialSidebarCategories | p99 | 79ms | 83ms | 4ms | 5.06
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | avg | 2ms | 0s | -2ms | -125.07
| RetentionPolicyStore.GetAll | avg | 4ms | 0s | -4ms | -106.02
| PostStore.GetPostsByIds | avg | 2ms | 0s | -2ms | -101.59
| ChannelStore.CreateSidebarCategory | avg | 22ms | 0s | -22ms | -100.04
| ChannelStore.GetChannelsByIds | avg | 2ms | 0s | -2ms | -97.00
| PostPersistentNotificationStore.UpdateLastActivity | avg | 3ms | 0s | -3ms | -94.76
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -89.98
| PostStore.SearchPostsForUser | avg | 69ms | 19ms | -50ms | -72.19
| UserAccessTokenStore.GetByToken | avg | 5ms | 2ms | -3ms | -61.20
| ChannelStore.AutocompleteInTeamForSearch | avg | 43ms | 28ms | -15ms | -35.17
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.93
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| RoleStore.GetByNames | p99 | 42ms | 5ms | -37ms | -88.10
| UserAccessTokenStore.GetByToken | p99 | 24ms | 5ms | -19ms | -79.33
| ThreadStore.MarkAllAsReadByChannels | p99 | 21ms | 5ms | -16ms | -75.29
| PostStore.GetPostReminderMetadata | p99 | 21ms | 5ms | -16ms | -74.77
| ChannelStore.GetMany | p99 | 20ms | 7ms | -13ms | -66.15
| PostStore.SearchPostsForUser | p99 | 871ms | 366ms | -505ms | -58.01
| PostStore.Update | p99 | 52ms | 25ms | -27ms | -52.41
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.52
| PostAcknowledgementStore.GetForPost | p99 | 17ms | 9ms | -8ms | -47.20
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.51
| ScheduledPostStore.CreateScheduledPost | p99 | 9ms | 5ms | -4ms | -44.44
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -42.55
| PropertyValueStore.SearchPropertyValues | p99 | 10ms | 6ms | -4ms | -42.09
| ChannelStore.CreateDirectChannel | p99 | 77ms | 49ms | -28ms | -36.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 88ms | 56ms | -32ms | -36.21
| PostPersistentNotificationStore.Get | p99 | 8ms | 5ms | -3ms | -35.93
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 7ms | 5ms | -2ms | -28.03
| FileInfoStore.AttachToPost | p99 | 28ms | 21ms | -7ms | -25.04
| UserStore.UpdateFailedPasswordAttempts | p99 | 31ms | 24ms | -7ms | -22.56
| ChannelStore.GetFileCount | p99 | 10ms | 8ms | -2ms | -20.43
| DraftStore.Upsert | p99 | 12ms | 10ms | -2ms | -16.28
| ChannelStore.SearchGroupChannels | p99 | 19ms | 16ms | -3ms | -16.09
| PreferenceStore.Save | p99 | 64ms | 54ms | -10ms | -15.60
| ClusterDiscoveryStore.SetLastPingAt | p99 | 21ms | 18ms | -3ms | -14.22
| ChannelStore.GetByName | p99 | 40ms | 35ms | -5ms | -12.55
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 20ms | 18ms | -2ms | -9.99
| ProductNoticesStore.View | p99 | 209ms | 191ms | -18ms | -8.63
| ChannelStore.SaveMember | p99 | 100ms | 98ms | -2ms | -2.00
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchAllChannels | avg | 33ms | 43ms | 10ms | 30.05
| createChannel | avg | 179ms | 199ms | 20ms | 11.16
| createUser | avg | 189ms | 191ms | 2ms | 1.06
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchAllChannels | p99 | 99ms | 389ms | 290ms | 293.89
| getServerLimits | p99 | 10ms | 25ms | 15ms | 150.75
| deletePost | p99 | 25ms | 49ms | 24ms | 96.55
| autocompleteUsers | p99 | 135ms | 153ms | 18ms | 13.30
| getChannel | p99 | 21ms | 23ms | 2ms | 9.68
| getProfileImage | p99 | 448ms | 458ms | 10ms | 2.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 10ms | 0s | -10ms | -102.86
| createCategoryForTeamForUser | avg | 26ms | 0s | -26ms | -98.37
| searchPostsInTeam | avg | 77ms | 26ms | -51ms | -65.83
| createSchedulePost | avg | 6ms | 3ms | -3ms | -53.14
| getChannelMembers | avg | 5ms | 3ms | -2ms | -41.41
| autocompleteChannelsForTeamForSearch | avg | 43ms | 28ms | -15ms | -35.11
| followThreadByUser | avg | 14ms | 12ms | -2ms | -14.66
| createDirectChannel | avg | 164ms | 154ms | -10ms | -6.09
| createGroupChannel | avg | 258ms | 243ms | -15ms | -5.82
| updateReadStateThreadByUser | avg | 35ms | 33ms | -2ms | -5.72
| addChannelMember | avg | 165ms | 157ms | -8ms | -4.84
| getProfileImage | avg | 95ms | 92ms | -3ms | -3.16
| removeUserCustomStatus | avg | 109ms | 106ms | -3ms | -2.76
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -101.01
| getFilteredUsersStats | p99 | 10ms | 0s | -10ms | -100.48
| createSchedulePost | p99 | 45ms | 5ms | -40ms | -88.89
| getChannelUnread | p99 | 21ms | 5ms | -16ms | -75.83
| searchPostsInTeam | p99 | 871ms | 389ms | -482ms | -55.37
| getPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.52
| listCPAValues | p99 | 10ms | 6ms | -4ms | -41.66
| createDirectChannel | p99 | 393ms | 248ms | -145ms | -36.94
| addChannelMember | p99 | 355ms | 250ms | -105ms | -29.57
| getDrafts | p99 | 10ms | 8ms | -2ms | -21.04
| getPostsForChannel | p99 | 125ms | 106ms | -19ms | -15.17
| updateReadStateThreadByUser | p99 | 80ms | 70ms | -10ms | -12.57
| getUser | p99 | 36ms | 32ms | -4ms | -11.22
| searchGroupChannels | p99 | 19ms | 17ms | -2ms | -10.73
| getTeamScheduledPosts | p99 | 39ms | 36ms | -3ms | -7.65
| getClientConfig | p99 | 50ms | 48ms | -2ms | -3.98
| patchPost | p99 | 52ms | 50ms | -2ms | -3.88
| addTeamMember | p99 | 2.228s | 2.153s | -75ms | -3.37
| createPost | p99 | 686ms | 671ms | -15ms | -2.19
| login | p99 | 500ms | 492ms | -8ms | -1.60
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 23ms | 18ms | 363.636
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 13ms| 12ms | -1ms | -7.685
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 42ms | 9ms | 27.202
| |  P99| 99ms| 389ms | 290ms | 293.885
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 43ms| 28ms | -15ms | -35.167
| |  P99| 99ms| 98ms | -1ms | -1.007
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 21ms | -1ms | -4.468
| |  P99| 77ms| 49ms | -28ms | -36.600
| ChannelStore.CreateInitialSidebarCategories |  Avg| 18ms| 19ms | 1ms | 5.407
| |  P99| 79ms| 83ms | 4ms | 5.065
| ChannelStore.CreateSidebarCategory |  Avg| 22ms| 0s | -22ms | -100.035
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.444
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 88ms| 56ms | -32ms | -36.209
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 35ms | -5ms | -12.546
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ChannelStore.GetChannelsByIds |  Avg| 2ms| 0s | -2ms | -97.002
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.430
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 7ms | -13ms | -66.146
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.863
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 13ms | -1ms | -7.385
| |  P99| 49ms| 25ms | -24ms | -48.525
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.117
| ChannelStore.GetTeamChannels |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 8.754
| |  P99| 25ms| 58ms | 33ms | 133.264
| ChannelStore.SaveMember |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 100ms| 98ms | -2ms | -2.000
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.089
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 38ms| 37ms | -1ms | -2.607
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.030
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.217
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.484
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 5ms | 1ms | 23.470
| |  P99| 10ms| 23ms | 13ms | 132.315
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.564
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.283
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 2ms | 1ms | 70.446
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 28ms| 21ms | -7ms | -25.036
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.876
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 5ms | 1ms | 22.578
| |  P99| 19ms| 19ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.227
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.988
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.844
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 90.702
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.757
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 9ms | -8ms | -47.199
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.928
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 0s | -3ms | -94.761
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 23ms | 6ms | 35.293
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 135ms| 198ms | 63ms | 46.630
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 16ms| 15ms | -1ms | -6.332
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.251
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.977
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 2ms | -1ms | -39.995
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 2ms | -1ms | -36.990
| |  P99| 21ms| 5ms | -16ms | -74.769
| PostStore.GetPostReminders |  Avg| 7ms| 6ms | -1ms | -13.699
| |  P99| 10ms| 92ms | 82ms | 824.121
| PostStore.GetPosts |  Avg| 4ms| 3ms | -1ms | -28.525
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.054
| PostStore.GetPostsByIds |  Avg| 2ms| 0s | -2ms | -101.592
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.005
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.347
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 69ms| 19ms | -50ms | -72.187
| |  P99| 871ms| 366ms | -505ms | -58.010
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 52ms| 25ms | -27ms | -52.411
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 4ms | 2ms | 92.075
| |  P99| 5ms| 46ms | 41ms | 828.283
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.471
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 64ms| 54ms | -10ms | -15.600
| ProductNoticesStore.ClearOldNotices |  Avg| 18ms| 17ms | -1ms | -5.640
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 2ms | 1ms | 67.735
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 209ms| 191ms | -18ms | -8.625
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.583
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 6ms | -4ms | -42.091
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.319
| RetentionPolicyStore.GetAll |  Avg| 4ms| 0s | -4ms | -106.023
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 2ms| 1ms | -1ms | -50.168
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 3ms| 2ms | -1ms | -37.295
| |  P99| 42ms| 5ms | -37ms | -88.095
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 3ms | -1ms | -27.456
| |  P99| 9ms| 5ms | -4ms | -44.443
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 6ms | 4ms | 218.984
| |  P99| 5ms| 92ms | 87ms | 1757.576
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 5ms | 3ms | 120.260
| |  P99| 5ms| 46ms | 41ms | 828.283
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -70.301
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.555
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 37ms| 36ms | -1ms | -2.729
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.205
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| StatusStore.SaveOrUpdateMany |  Avg| 7ms| 6ms | -1ms | -14.431
| |  P99| 42ms| 58ms | 16ms | 37.872
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 28ms | 22ms | 396.396
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.505
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.385
| SystemStore.PermanentDeleteByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.431
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.524
| TeamStore.GetMany |  Avg| 2ms| 0s | -2ms | -125.072
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.777
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.600
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.410
| TeamStore.GetTotalMemberCount |  Avg| 35ms| 34ms | -1ms | -2.879
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 69ms| 69ms | 0s | 0.000
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.248
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.241
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.247
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.155
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.966
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -75.291
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.692
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 6ms | 4ms | 180.925
| |  P99| 5ms| 25ms | 20ms | 403.897
| UserAccessTokenStore.GetByToken |  Avg| 5ms| 2ms | -3ms | -61.201
| |  P99| 24ms| 5ms | -19ms | -79.333
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 13ms | -1ms | -7.262
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 1ms | -1ms | -61.951
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 164ms| 176ms | 12ms | 7.300
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| UserStore.Get |  Avg| 3ms| 2ms | -1ms | -39.967
| |  P99| 18ms| 17ms | -1ms | -5.655
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 147ms| 148ms | 1ms | 0.680
| |  P99| 472ms| 473ms | 1ms | 0.212
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 17ms | 12ms | 242.424
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.372
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -89.976
| |  P99| 5ms| 0s | -5ms | -100.929
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.345
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 10ms| 19ms | 9ms | 89.444
| |  P99| 25ms| 233ms | 208ms | 838.708
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.192
| UserStore.Save |  Avg| 126ms| 127ms | 1ms | 0.792
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.020
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.246
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 4ms | -1ms | -21.456
| |  P99| 31ms| 24ms | -7ms | -22.556
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.213
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.374
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.499
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 165ms| 157ms | -8ms | -4.842
| | P99| 355ms| 250ms | -105ms | -29.574
| addTeamMember | Avg| 607ms| 609ms | 2ms | 0.330
| | P99| 2.228s| 2.153s | -75ms | -3.367
| autocompleteChannelsForTeamForSearch | Avg| 43ms| 28ms | -15ms | -35.114
| | P99| 99ms| 98ms | -1ms | -1.007
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 135ms| 153ms | 18ms | 13.296
| createCategoryForTeamForUser | Avg| 26ms| 0s | -26ms | -98.375
| | P99| 50ms| 0s | -50ms | -101.010
| createChannel | Avg| 179ms| 199ms | 20ms | 11.158
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 17ms| 16ms | -1ms | -5.833
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 164ms| 154ms | -10ms | -6.090
| | P99| 393ms| 248ms | -145ms | -36.940
| createGroupChannel | Avg| 258ms| 243ms | -15ms | -5.821
| | P99| 496ms| 495ms | -1ms | -0.202
| createPost | Avg| 150ms| 150ms | 0s | 0.000
| | P99| 686ms| 671ms | -15ms | -2.188
| createSchedulePost | Avg| 6ms| 3ms | -3ms | -53.136
| | P99| 45ms| 5ms | -40ms | -88.886
| createUser | Avg| 189ms| 191ms | 2ms | 1.061
| | P99| 481ms| 480ms | -1ms | -0.208
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 25ms| 49ms | 24ms | 96.549
| followThreadByUser | Avg| 14ms| 12ms | -2ms | -14.657
| | P99| 25ms| 25ms | 0s | 0.000
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getAnalytics | Avg| 26ms| 27ms | 1ms | 3.816
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 39ms| 40ms | 1ms | 2.550
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.683
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 44ms| 44ms | 0s | 0.000
| getChannelMembers | Avg| 5ms| 3ms | -2ms | -41.415
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.826
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 27ms | -1ms | -3.580
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 5ms | -16ms | -75.827
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 15ms | 0s | 0.000
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 50ms| 48ms | -2ms | -3.982
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 2ms | -1ms | -38.973
| | P99| 10ms| 8ms | -2ms | -21.036
| getFilePreview | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| getFileThumbnail | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 93ms| 93ms | 0s | 0.000
| getFilteredUsersStats | Avg| 10ms| 0s | -10ms | -102.862
| | P99| 10ms| 0s | -10ms | -100.483
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.562
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 18ms| 17ms | -1ms | -5.627
| | P99| 125ms| 106ms | -19ms | -15.166
| getPostsForChannelAroundLastUnread | Avg| 18ms| 17ms | -1ms | -5.673
| | P99| 90ms| 89ms | -1ms | -1.109
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 95ms| 92ms | -3ms | -3.158
| | P99| 448ms| 458ms | 10ms | 2.231
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 49ms| 25ms | -24ms | -48.525
| getRolesByNames | Avg| 4ms| 5ms | 1ms | 23.316
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 10ms| 25ms | 15ms | 150.754
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.353
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 36ms | -3ms | -7.654
| getTeamStats | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 2ms | -1ms | -39.667
| | P99| 22ms| 22ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 37ms| 37ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 36ms| 32ms | -4ms | -11.220
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 29ms| 30ms | 1ms | 3.489
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| listCPAValues | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 6ms | -4ms | -41.662
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 108ms| 107ms | -1ms | -0.928
| | P99| 500ms| 492ms | -8ms | -1.600
| logout | Avg| 23ms| 22ms | -1ms | -4.324
| | P99| 48ms| 48ms | 0s | 0.000
| patchPost | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 52ms| 50ms | -2ms | -3.882
| removeUserCustomStatus | Avg| 109ms| 106ms | -3ms | -2.762
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.073
| searchAllChannels | Avg| 33ms| 43ms | 10ms | 30.050
| | P99| 99ms| 389ms | 290ms | 293.885
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 17ms | -2ms | -10.726
| searchPostsInTeam | Avg| 77ms| 26ms | -51ms | -65.833
| | P99| 871ms| 389ms | -482ms | -55.368
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 18ms| 17ms | -1ms | -5.597
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 12ms | -1ms | -7.537
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 54ms| 53ms | -1ms | -1.852
| | P99| 99ms| 99ms | 0s | 0.000
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 35ms| 33ms | -2ms | -5.718
| | P99| 80ms| 70ms | -10ms | -12.574
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 408ms| 405ms | -3ms | -0.734
| | P99| 988ms| 989ms | 1ms | 0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 16ms| 15ms | -1ms | -6.145
| viewChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 29ms| 29ms | 0s | 0.000
