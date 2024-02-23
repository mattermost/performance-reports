### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 4ms | 60ms | 56ms | 1334.37
| TeamStore.AnalyticsTeamCount | avg | 1ms | 3ms | 2ms | 165.61
| UserStore.GetProfilesInChannel | avg | 108ms | 187ms | 79ms | 72.99
| JobStore.Save | avg | 4ms | 7ms | 3ms | 69.33
| SessionStore.Remove | avg | 3ms | 5ms | 2ms | 60.22
| RoleStore.ChannelHigherScopedPermissions | avg | 4ms | 6ms | 2ms | 53.23
| ChannelStore.GetMembersForUserWithPagination | avg | 14ms | 18ms | 4ms | 28.46
| UserStore.Count | avg | 14ms | 16ms | 2ms | 14.05
| UserStore.AnalyticsActiveCount | avg | 20ms | 22ms | 2ms | 10.25
| UserStore.GetAllProfilesInChannel | avg | 250ms | 257ms | 7ms | 2.80
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 22ms | 764ms | 742ms | 3334.71
| PostPersistentNotificationStore.Get | p99 | 5ms | 43ms | 38ms | 767.68
| JobStore.Save | p99 | 18ms | 88ms | 70ms | 389.97
| SessionStore.Remove | p99 | 5ms | 24ms | 19ms | 383.84
| UserStore.GetMany | p99 | 5ms | 23ms | 18ms | 363.64
| ChannelStore.Save | p99 | 42ms | 140ms | 98ms | 232.64
| ChannelStore.GetMembersForUserWithPagination | p99 | 25ms | 79ms | 54ms | 218.03
| RoleStore.ChannelHigherScopedPermissions | p99 | 9ms | 24ms | 15ms | 159.61
| PostStore.GetPostReminderMetadata | p99 | 9ms | 23ms | 14ms | 151.33
| ChannelStore.GetChannelsByUser | p99 | 10ms | 25ms | 15ms | 150.38
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| UserStore.GetByUsername | p99 | 10ms | 23ms | 13ms | 135.18
| JobStore.Get | p99 | 8ms | 18ms | 10ms | 130.70
| TeamStore.GetMember | p99 | 8ms | 17ms | 9ms | 109.90
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 10ms | 5ms | 101.01
| PluginStore.Get | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.AnalyticsActiveCount | p99 | 25ms | 48ms | 23ms | 92.56
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetPublicChannelsForTeam | p99 | 40ms | 70ms | 30ms | 74.98
| UserStore.Get | p99 | 12ms | 20ms | 8ms | 65.37
| UserStore.Update | p99 | 42ms | 68ms | 26ms | 61.38
| LinkMetadataStore.Save | p99 | 5ms | 8ms | 3ms | 60.59
| ChannelStore.CreateDirectChannel | p99 | 91ms | 137ms | 46ms | 50.55
| ChannelStore.GetAllChannelMembersForUser | p99 | 11ms | 16ms | 5ms | 47.57
| PostPersistentNotificationStore.GetSingle | p99 | 10ms | 14ms | 4ms | 40.97
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 5ms | 7ms | 2ms | 40.01
| JobStore.GetNewestJobByStatusesAndType | p99 | 18ms | 22ms | 4ms | 22.66
| PostAcknowledgementStore.GetForPost | p99 | 18ms | 22ms | 4ms | 21.87
| PluginStore.List | p99 | 19ms | 22ms | 3ms | 15.79
| ThreadStore.MarkAsRead | p99 | 14ms | 16ms | 2ms | 14.08
| PostStore.Get | p99 | 30ms | 34ms | 4ms | 13.47
| UserStore.GetUnreadCount | p99 | 20ms | 22ms | 2ms | 10.17
| ThreadStore.MaintainMembership | p99 | 27ms | 29ms | 2ms | 7.43
| ChannelStore.GetGuestCount | p99 | 30ms | 32ms | 2ms | 6.62
| WebhookStore.GetOutgoingByTeam | p99 | 33ms | 35ms | 2ms | 6.06
| ChannelStore.GetByName | p99 | 36ms | 38ms | 2ms | 5.50
| UserStore.Count | p99 | 45ms | 47ms | 2ms | 4.44
| PostStore.Save | p99 | 56ms | 58ms | 2ms | 3.56
| UserStore.Save | p99 | 214ms | 218ms | 4ms | 1.87
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -119.83
| BotStore.Save | avg | 3ms | 0s | -3ms | -89.64
| SessionStore.GetSessionsExpired | avg | 8ms | 2ms | -6ms | -78.63
| ChannelStore.AutocompleteInTeamForSearch | avg | 89ms | 21ms | -68ms | -76.59
| ChannelStore.SearchGroupChannels | avg | 12ms | 4ms | -8ms | -64.72
| PreferenceStore.DeleteCategoryAndName | avg | 5ms | 2ms | -3ms | -63.97
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 33ms | 15ms | -18ms | -54.46
| ChannelStore.CreateInitialSidebarCategories | avg | 46ms | 24ms | -22ms | -48.25
| ChannelStore.GetSidebarCategory | avg | 17ms | 9ms | -8ms | -47.44
| PostStore.AnalyticsPostCount | avg | 809ms | 449ms | -360ms | -44.51
| ChannelStore.UpdateSidebarCategories | avg | 75ms | 47ms | -28ms | -37.32
| ChannelStore.CreateSidebarCategory | avg | 42ms | 27ms | -15ms | -35.73
| PostStore.GetPostReminders | avg | 11ms | 9ms | -2ms | -18.76
| ChannelStore.AnalyticsTypeCount | avg | 14ms | 12ms | -2ms | -14.55
| PostStore.SearchPostsForUser | avg | 194ms | 191ms | -3ms | -1.54
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.669s | 88ms | -3.581s | -97.61
| ThreadStore.MarkAllAsReadByChannels | p99 | 42ms | 5ms | -37ms | -87.58
| SessionStore.GetSessionsExpired | p99 | 48ms | 10ms | -38ms | -78.76
| PostStore.GetPostsAfter | p99 | 42ms | 9ms | -33ms | -78.57
| PreferenceStore.DeleteCategoryAndName | p99 | 23ms | 5ms | -18ms | -78.09
| ThreadStore.Get | p99 | 21ms | 5ms | -16ms | -78.05
| JobStore.GetCountByStatusAndType | p99 | 18ms | 5ms | -13ms | -73.65
| JobStore.UpdateOptimistically | p99 | 76ms | 21ms | -55ms | -72.37
| UserAccessTokenStore.GetByToken | p99 | 23ms | 9ms | -14ms | -61.95
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 8ms | -10ms | -56.18
| TeamStore.GetByName | p99 | 19ms | 9ms | -10ms | -53.91
| JobStore.UpdateStatus | p99 | 38ms | 18ms | -20ms | -52.63
| PostStore.AnalyticsPostCount | p99 | 995ms | 498ms | -497ms | -49.95
| PostStore.GetPostReminders | p99 | 91ms | 46ms | -45ms | -49.18
| ChannelStore.GetSidebarCategory | p99 | 49ms | 25ms | -24ms | -48.55
| ChannelStore.GetTeamChannels | p99 | 48ms | 25ms | -23ms | -47.92
| ChannelStore.UpdateSidebarCategories | p99 | 413ms | 222ms | -191ms | -46.30
| ChannelStore.SearchGroupChannels | p99 | 42ms | 24ms | -18ms | -42.42
| StatusStore.GetByIds | p99 | 24ms | 15ms | -9ms | -37.37
| ChannelStore.GetChannelUnread | p99 | 8ms | 5ms | -3ms | -35.71
| ClusterDiscoveryStore.SetLastPingAt | p99 | 28ms | 20ms | -8ms | -28.83
| FileInfoStore.Save | p99 | 34ms | 25ms | -9ms | -26.43
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 96ms | 73ms | -23ms | -23.84
| ChannelStore.CreateInitialSidebarCategories | p99 | 187ms | 143ms | -44ms | -23.47
| EmojiStore.GetByName | p99 | 17ms | 13ms | -4ms | -23.20
| FileInfoStore.Get | p99 | 14ms | 11ms | -3ms | -21.07
| ReactionStore.GetForPost | p99 | 23ms | 19ms | -4ms | -17.06
| PostStore.GetSingle | p99 | 12ms | 10ms | -2ms | -16.03
| ThreadStore.UpdateMembership | p99 | 13ms | 11ms | -2ms | -14.83
| LinkMetadataStore.Get | p99 | 15ms | 13ms | -2ms | -13.70
| PostPriorityStore.GetForPost | p99 | 23ms | 20ms | -3ms | -13.26
| PluginStore.SetWithOptions | p99 | 38ms | 33ms | -5ms | -13.21
| GroupStore.GetByName | p99 | 27ms | 24ms | -3ms | -11.00
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 46ms | 41ms | -5ms | -10.96
| UserStore.AutocompleteUsersInChannel | p99 | 327ms | 293ms | -34ms | -10.39
| StatusStore.UpdateLastActivityAt | p99 | 20ms | 18ms | -2ms | -10.14
| FileInfoStore.SetContent | p99 | 50ms | 45ms | -5ms | -10.05
| JobStore.GetAllByStatus | p99 | 25ms | 23ms | -2ms | -8.06
| TeamStore.GetTeamsForUser | p99 | 27ms | 25ms | -2ms | -7.52
| ThreadStore.GetTeamsUnreadForUser | p99 | 30ms | 28ms | -2ms | -6.70
| PreferenceStore.GetAll | p99 | 32ms | 30ms | -2ms | -6.16
| TeamStore.SaveMember | p99 | 99ms | 97ms | -2ms | -2.01
| UserStore.GetAllProfilesInChannel | p99 | 915ms | 904ms | -11ms | -1.20
| ChannelStore.SaveMember | p99 | 181ms | 179ms | -2ms | -1.11
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 2ms | 8ms | 6ms | 354.00
| deleteDraft | avg | 2ms | 5ms | 3ms | 195.35
| logout | avg | 49ms | 61ms | 12ms | 24.43
| getChannelMembersForUser | avg | 9ms | 11ms | 2ms | 21.06
| removeUserCustomStatus | avg | 161ms | 177ms | 16ms | 9.96
| createDirectChannel | avg | 245ms | 259ms | 14ms | 5.70
| createPost | avg | 326ms | 331ms | 5ms | 1.54
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| unfollowThreadByUser | p99 | 44ms | 133ms | 89ms | 201.35
| logout | p99 | 94ms | 232ms | 138ms | 147.59
| getRolesByNames | p99 | 5ms | 10ms | 5ms | 101.01
| getChannel | p99 | 16ms | 32ms | 16ms | 100.47
| deletePost | p99 | 25ms | 47ms | 22ms | 88.51
| getPublicChannelsForTeam | p99 | 44ms | 70ms | 26ms | 59.11
| getChannelsForUser | p99 | 165ms | 214ms | 49ms | 29.65
| createUser | p99 | 290ms | 336ms | 46ms | 15.85
| getPostThread | p99 | 50ms | 53ms | 3ms | 6.03
| patchPost | p99 | 197ms | 208ms | 11ms | 5.58
| setPostReminder | p99 | 46ms | 48ms | 2ms | 4.35
| viewChannel | p99 | 58ms | 60ms | 2ms | 3.42
| removeUserCustomStatus | p99 | 478ms | 487ms | 9ms | 1.88
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -115.64
| getProductNotices | avg | 2ms | 0s | -2ms | -100.84
| getDrafts | avg | 2ms | 0s | -2ms | -94.92
| autocompleteChannelsForTeamForSearch | avg | 89ms | 21ms | -68ms | -76.55
| searchGroupChannels | avg | 12ms | 4ms | -8ms | -64.37
| getCategoriesForTeamForUser | avg | 33ms | 16ms | -17ms | -50.94
| updateCategoriesForTeamForUser | avg | 111ms | 66ms | -45ms | -40.61
| followThreadByUser | avg | 20ms | 13ms | -7ms | -35.12
| createCategoryForTeamForUser | avg | 44ms | 29ms | -15ms | -34.26
| getProfileImage | avg | 96ms | 94ms | -2ms | -2.09
| searchPostsInTeam | avg | 202ms | 198ms | -4ms | -1.98
| createGroupChannel | avg | 385ms | 379ms | -6ms | -1.56
| addTeamMember | avg | 852ms | 842ms | -10ms | -1.17
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUserLimits | p99 | 5ms | 0s | -5ms | -101.01
| getDrafts | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getSelfHostedProducts | p99 | 5ms | 0s | -5ms | -100.13
| autocompleteChannelsForTeamForSearch | p99 | 3.669s | 88ms | -3.581s | -97.61
| followThreadByUser | p99 | 95ms | 25ms | -70ms | -73.68
| getTeamMember | p99 | 22ms | 10ms | -12ms | -55.62
| createChannel | p99 | 48ms | 25ms | -23ms | -47.92
| updateCategoriesForTeamForUser | p99 | 413ms | 222ms | -191ms | -46.30
| searchGroupChannels | p99 | 42ms | 24ms | -18ms | -42.42
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -42.25
| createDirectChannel | p99 | 798ms | 499ms | -299ms | -37.45
| getUsers | p99 | 70ms | 52ms | -18ms | -25.84
| getCategoriesForTeamForUser | p99 | 97ms | 76ms | -21ms | -21.60
| updateReadStateThreadByUser | p99 | 157ms | 139ms | -18ms | -11.44
| createPost | p99 | 1.673s | 1.486s | -187ms | -11.18
| getChannelMember | p99 | 72ms | 65ms | -7ms | -9.78
| getTeamMembersForUser | p99 | 39ms | 36ms | -3ms | -7.60
| autocompleteUsers | p99 | 222ms | 210ms | -12ms | -5.42
| getTeamsUnreadForUser | p99 | 45ms | 43ms | -2ms | -4.46
| getPostsForChannel | p99 | 213ms | 207ms | -6ms | -2.81
| getPostsForChannelAroundLastUnread | p99 | 155ms | 151ms | -4ms | -2.58
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.021
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.454
| BotStore.Save |  Avg| 3ms| 0s | -3ms | -89.640
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 14ms| 12ms | -2ms | -14.549
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 45ms| 46ms | 1ms | 2.217
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 89ms| 21ms | -68ms | -76.594
| |  P99| 3.669s| 88ms | -3.581s | -97.608
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 23ms | 1ms | 4.557
| |  P99| 91ms| 137ms | 46ms | 50.549
| ChannelStore.CreateInitialSidebarCategories |  Avg| 46ms| 24ms | -22ms | -48.251
| |  P99| 187ms| 143ms | -44ms | -23.468
| ChannelStore.CreateSidebarCategory |  Avg| 42ms| 27ms | -15ms | -35.729
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 13ms| 14ms | 1ms | 7.875
| |  P99| 46ms| 41ms | -5ms | -10.959
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 16ms | 5ms | 47.567
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 38ms | 2ms | 5.501
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.713
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.485
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 4ms | 1ms | 29.784
| |  P99| 10ms| 25ms | 15ms | 150.376
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.487
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 32ms | 2ms | 6.620
| ChannelStore.GetMember |  Avg| 4ms| 3ms | -1ms | -28.185
| |  P99| 25ms| 24ms | -1ms | -4.073
| ChannelStore.GetMemberCount |  Avg| 23ms| 22ms | -1ms | -4.407
| |  P99| 83ms| 82ms | -1ms | -1.210
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.995
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 14ms| 18ms | 4ms | 28.460
| |  P99| 25ms| 79ms | 54ms | 218.028
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 19ms | 1ms | 5.634
| |  P99| 40ms| 70ms | 30ms | 74.976
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 33ms| 15ms | -18ms | -54.457
| |  P99| 96ms| 73ms | -23ms | -23.841
| ChannelStore.GetSidebarCategory |  Avg| 17ms| 9ms | -8ms | -47.443
| |  P99| 49ms| 25ms | -24ms | -48.548
| ChannelStore.GetTeamChannels |  Avg| 19ms| 18ms | -1ms | -5.215
| |  P99| 48ms| 25ms | -23ms | -47.917
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 11ms | 1ms | 9.886
| |  P99| 42ms| 140ms | 98ms | 232.641
| ChannelStore.SaveMember |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 181ms| 179ms | -2ms | -1.108
| ChannelStore.SearchGroupChannels |  Avg| 12ms| 4ms | -8ms | -64.717
| |  P99| 42ms| 24ms | -18ms | -42.421
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 75ms| 47ms | -28ms | -37.323
| |  P99| 413ms| 222ms | -191ms | -46.302
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.012
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 20ms | -8ms | -28.829
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 13ms | -4ms | -23.204
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 8ms| 7ms | -1ms | -13.208
| |  P99| 25ms| 25ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.065
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 6ms| 5ms | -1ms | -17.539
| |  P99| 34ms| 25ms | -9ms | -26.426
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 50ms| 45ms | -5ms | -10.051
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 24ms | -3ms | -11.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 130.699
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -8.062
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -65.103
| |  P99| 18ms| 5ms | -13ms | -73.654
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.663
| JobStore.Save |  Avg| 4ms| 7ms | 3ms | 69.326
| |  P99| 18ms| 88ms | 70ms | 389.972
| JobStore.UpdateOptimistically |  Avg| 5ms| 4ms | -1ms | -18.659
| |  P99| 76ms| 21ms | -55ms | -72.368
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -20.626
| |  P99| 38ms| 18ms | -20ms | -52.632
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -56.180
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.699
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.589
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.863
| PluginStore.Get |  Avg| 1ms| 2ms | 1ms | 76.331
| |  P99| 5ms| 10ms | 5ms | 101.010
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.789
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -14.775
| |  P99| 38ms| 33ms | -5ms | -13.208
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 21.873
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.738
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 2ms| 3ms | 1ms | 51.771
| |  P99| 5ms| 43ms | 38ms | 767.677
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 2ms | 1ms | 66.967
| |  P99| 10ms| 14ms | 4ms | 40.973
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.257
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.514
| PostStore.AnalyticsPostCount |  Avg| 809ms| 449ms | -360ms | -44.508
| |  P99| 995ms| 498ms | -497ms | -49.950
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.503
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 34ms | 4ms | 13.474
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.050
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 4ms | 1ms | 36.297
| |  P99| 9ms| 23ms | 14ms | 151.335
| PostStore.GetPostReminders |  Avg| 11ms| 9ms | -2ms | -18.756
| |  P99| 91ms| 46ms | -45ms | -49.180
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.027
| PostStore.GetPostsAfter |  Avg| 4ms| 3ms | -1ms | -26.404
| |  P99| 42ms| 9ms | -33ms | -78.572
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.357
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.034
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 56ms| 58ms | 2ms | 3.557
| PostStore.SearchPostsForUser |  Avg| 194ms| 191ms | -3ms | -1.543
| |  P99| 2.358s| 2.362s | 4ms | 0.170
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 14.156
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.012
| PreferenceStore.DeleteCategoryAndName |  Avg| 5ms| 2ms | -3ms | -63.968
| |  P99| 23ms| 5ms | -18ms | -78.091
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 30ms | -2ms | -6.160
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 75ms| 74ms | -1ms | -1.325
| ProductNoticesStore.ClearOldNotices |  Avg| 27ms| 28ms | 1ms | 3.663
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 43ms| 43ms | 0s | 0.000
| |  P99| 233ms| 234ms | 1ms | 0.430
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.056
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 6ms | 2ms | 53.226
| |  P99| 9ms| 24ms | 15ms | 159.612
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 48ms | 1ms | 2.119
| SessionStore.GetSessionsExpired |  Avg| 8ms| 2ms | -6ms | -78.634
| |  P99| 48ms| 10ms | -38ms | -78.756
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.439
| SessionStore.Remove |  Avg| 3ms| 5ms | 2ms | 60.218
| |  P99| 5ms| 24ms | 19ms | 383.838
| SessionStore.Save |  Avg| 8ms| 7ms | -1ms | -13.189
| |  P99| 45ms| 44ms | -1ms | -2.201
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.320
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 15ms | -9ms | -37.366
| StatusStore.SaveOrUpdate |  Avg| 4ms| 60ms | 56ms | 1334.372
| |  P99| 22ms| 764ms | 742ms | 3334.712
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.140
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 3ms | 2ms | 165.610
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 2ms | 1ms | 66.714
| |  P99| 13ms| 13ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.096
| TeamStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 9ms | -10ms | -53.908
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 17ms | 9ms | 109.896
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.517
| TeamStore.SaveMember |  Avg| 30ms| 29ms | -1ms | -3.339
| |  P99| 99ms| 97ms | -2ms | -2.012
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -49.440
| |  P99| 21ms| 5ms | -16ms | -78.049
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.119
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 28ms | -2ms | -6.700
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.086
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.236
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.147
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.203
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.214
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 27ms| 29ms | 2ms | 7.432
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 3ms | -1ms | -23.181
| |  P99| 42ms| 5ms | -37ms | -87.576
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -119.826
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.078
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -14.825
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 9ms | -14ms | -61.947
| UserStore.AnalyticsActiveCount |  Avg| 20ms| 22ms | 2ms | 10.247
| |  P99| 25ms| 48ms | 23ms | 92.555
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 2ms | 1ms | 138.277
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 327ms| 293ms | -34ms | -10.390
| UserStore.Count |  Avg| 14ms| 16ms | 2ms | 14.050
| |  P99| 45ms| 47ms | 2ms | 4.444
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 20ms | 8ms | 65.368
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.371
| UserStore.GetAllProfilesInChannel |  Avg| 250ms| 257ms | 7ms | 2.801
| |  P99| 915ms| 904ms | -11ms | -1.202
| UserStore.GetByUsername |  Avg| 2ms| 3ms | 1ms | 50.992
| |  P99| 10ms| 23ms | 13ms | 135.182
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.193
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 60.573
| |  P99| 5ms| 23ms | 18ms | 363.636
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.974
| UserStore.GetProfilesInChannel |  Avg| 108ms| 187ms | 79ms | 72.987
| |  P99| 247ms| 249ms | 2ms | 0.809
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.168
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.519
| UserStore.Save |  Avg| 72ms| 72ms | 0s | 0.000
| |  P99| 214ms| 218ms | 4ms | 1.869
| UserStore.Search |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 9ms| 8ms | -1ms | -11.699
| |  P99| 42ms| 68ms | 26ms | 61.376
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.836
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.029
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 5ms | 1ms | 23.523
| |  P99| 33ms| 35ms | 2ms | 6.056
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 249ms| 249ms | 0s | 0.000
| | P99| 495ms| 495ms | 0s | 0.000
| addTeamMember | Avg| 852ms| 842ms | -10ms | -1.173
| | P99| 2.455s| 2.439s | -16ms | -0.652
| autocompleteChannelsForTeamForSearch | Avg| 89ms| 21ms | -68ms | -76.546
| | P99| 3.669s| 88ms | -3.581s | -97.608
| autocompleteUsers | Avg| 41ms| 42ms | 1ms | 2.468
| | P99| 222ms| 210ms | -12ms | -5.418
| createCategoryForTeamForUser | Avg| 44ms| 29ms | -15ms | -34.255
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 19ms| 18ms | -1ms | -5.179
| | P99| 48ms| 25ms | -23ms | -47.917
| createDirectChannel | Avg| 245ms| 259ms | 14ms | 5.705
| | P99| 798ms| 499ms | -299ms | -37.453
| createGroupChannel | Avg| 385ms| 379ms | -6ms | -1.560
| | P99| 965ms| 965ms | 0s | 0.000
| createPost | Avg| 326ms| 331ms | 5ms | 1.536
| | P99| 1.673s| 1.486s | -187ms | -11.177
| createUser | Avg| 102ms| 102ms | 0s | 0.000
| | P99| 290ms| 336ms | 46ms | 15.849
| deleteDraft | Avg| 2ms| 5ms | 3ms | 195.349
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 20ms| 19ms | -1ms | -5.125
| | P99| 25ms| 47ms | 22ms | 88.514
| followThreadByUser | Avg| 20ms| 13ms | -7ms | -35.117
| | P99| 95ms| 25ms | -70ms | -73.685
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 30ms| 31ms | 1ms | 3.315
| getCategoriesForTeamForUser | Avg| 33ms| 16ms | -17ms | -50.942
| | P99| 97ms| 76ms | -21ms | -21.603
| getChannel | Avg| 4ms| 5ms | 1ms | 22.655
| | P99| 16ms| 32ms | 16ms | 100.471
| getChannelMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 72ms| 65ms | -7ms | -9.781
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelMembersForUser | Avg| 9ms| 11ms | 2ms | 21.063
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -2.012
| getChannelUnread | Avg| 3ms| 2ms | -1ms | -37.758
| | P99| 9ms| 5ms | -4ms | -42.253
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelsForUser | Avg| 6ms| 7ms | 1ms | 18.170
| | P99| 165ms| 214ms | 49ms | 29.654
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 65ms| 65ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 0s | -2ms | -94.915
| | P99| 5ms| 0s | -5ms | -101.010
| getFilePreview | Avg| 44ms| 44ms | 0s | 0.000
| | P99| 206ms| 207ms | 1ms | 0.485
| getFileThumbnail | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 100ms| 99ms | -1ms | -1.001
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 64ms| 64ms | 0s | 0.000
| | P99| 100ms| 100ms | 0s | 0.000
| getPostThread | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 50ms| 53ms | 3ms | 6.033
| getPostsForChannel | Avg| 23ms| 22ms | -1ms | -4.373
| | P99| 213ms| 207ms | -6ms | -2.815
| getPostsForChannelAroundLastUnread | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 155ms| 151ms | -4ms | -2.578
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 34ms| 33ms | -1ms | -2.918
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 2ms| 0s | -2ms | -100.844
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 96ms| 94ms | -2ms | -2.089
| | P99| 472ms| 476ms | 4ms | 0.847
| getPublicChannelsForTeam | Avg| 19ms| 20ms | 1ms | 5.258
| | P99| 44ms| 70ms | 26ms | 59.113
| getRolesByNames | Avg| 2ms| 8ms | 6ms | 354.002
| | P99| 5ms| 10ms | 5ms | 101.010
| getSelfHostedProducts | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -100.127
| getTeamMember | Avg| 3ms| 2ms | -1ms | -35.192
| | P99| 22ms| 10ms | -12ms | -55.619
| getTeamMembersForUser | Avg| 4ms| 3ms | -1ms | -28.203
| | P99| 39ms| 36ms | -3ms | -7.603
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 45ms| 43ms | -2ms | -4.459
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 46ms| 45ms | -1ms | -2.153
| getUserLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 6ms | -1ms | -14.227
| | P99| 70ms| 52ms | -18ms | -25.839
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 72ms| 73ms | 1ms | 1.387
| | P99| 407ms| 410ms | 3ms | 0.737
| logout | Avg| 49ms| 61ms | 12ms | 24.427
| | P99| 94ms| 232ms | 138ms | 147.592
| patchPost | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 197ms| 208ms | 11ms | 5.584
| removeUserCustomStatus | Avg| 161ms| 177ms | 16ms | 9.960
| | P99| 478ms| 487ms | 9ms | 1.882
| root | Avg| 0s| 1ms | 1ms | 811.201
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 56ms| 57ms | 1ms | 1.798
| searchAllChannels | Avg| 45ms| 46ms | 1ms | 2.198
| | P99| 100ms| 100ms | 0s | 0.000
| searchGroupChannels | Avg| 12ms| 4ms | -8ms | -64.375
| | P99| 42ms| 24ms | -18ms | -42.421
| searchPostsInTeam | Avg| 202ms| 198ms | -4ms | -1.978
| | P99| 2.375s| 2.366s | -9ms | -0.379
| searchUsers | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 99ms | 1ms | 1.018
| setPostReminder | Avg| 19ms| 20ms | 1ms | 5.332
| | P99| 46ms| 48ms | 2ms | 4.347
| unfollowThreadByUser | Avg| 14ms| 15ms | 1ms | 6.980
| | P99| 44ms| 133ms | 89ms | 201.347
| updateCategoriesForTeamForUser | Avg| 111ms| 66ms | -45ms | -40.609
| | P99| 413ms| 222ms | -191ms | -46.302
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -115.637
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 157ms| 139ms | -18ms | -11.439
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 434ms| 432ms | -2ms | -0.461
| | P99| 999ms| 998ms | -1ms | -0.100
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 58ms| 60ms | 2ms | 3.425
