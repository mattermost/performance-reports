### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 2ms | 6ms | 4ms | 199.85
| UserStore.Count | avg | 26ms | 68ms | 42ms | 159.03
| UserStore.GetAllProfiles | avg | 4ms | 10ms | 6ms | 152.05
| StatusStore.SaveOrUpdate | avg | 33ms | 46ms | 13ms | 39.43
| ChannelStore.AutocompleteInTeamForSearch | avg | 285ms | 350ms | 65ms | 22.81
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetAllProfiles | p99 | 27ms | 224ms | 197ms | 719.66
| UserStore.GetMany | p99 | 5ms | 23ms | 18ms | 363.64
| JobStore.GetCountByStatusAndType | p99 | 5ms | 18ms | 13ms | 262.63
| ClusterDiscoveryStore.SetLastPingAt | p99 | 10ms | 28ms | 18ms | 182.29
| UserStore.Update | p99 | 10ms | 23ms | 13ms | 130.05
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 11ms | 6ms | 121.21
| UserAccessTokenStore.GetByToken | p99 | 5ms | 10ms | 5ms | 101.01
| TokenStore.Cleanup | p99 | 5ms | 10ms | 5ms | 100.95
| UserStore.Count | p99 | 50ms | 99ms | 49ms | 98.55
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.328s | 3.826s | 1.498s | 64.35
| TeamStore.GetTeamsForUser | p99 | 10ms | 16ms | 6ms | 61.46
| ThreadStore.Get | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.IsEmpty | p99 | 5ms | 8ms | 3ms | 58.06
| TeamStore.SaveMember | p99 | 100ms | 144ms | 44ms | 44.00
| FileInfoStore.GetForPost | p99 | 5ms | 7ms | 2ms | 39.88
| GroupStore.GetByName | p99 | 11ms | 14ms | 3ms | 28.16
| ChannelStore.IncrementMentionCount | p99 | 11ms | 14ms | 3ms | 26.61
| PostStore.GetEtag | p99 | 12ms | 15ms | 3ms | 25.53
| UserStore.GetForLogin | p99 | 12ms | 15ms | 3ms | 24.84
| UserTermsOfServiceStore.GetByUser | p99 | 10ms | 12ms | 2ms | 20.23
| SessionStore.Get | p99 | 27ms | 31ms | 4ms | 14.79
| SystemStore.GetByName | p99 | 14ms | 16ms | 2ms | 13.96
| ChannelStore.GetPublicChannelsForTeam | p99 | 20ms | 22ms | 2ms | 9.77
| PostStore.SetPostReminder | p99 | 23ms | 25ms | 2ms | 8.51
| StatusStore.SaveOrUpdate | p99 | 451ms | 468ms | 17ms | 3.77
| ProductNoticesStore.View | p99 | 145ms | 149ms | 4ms | 2.76
| ChannelStore.SaveMember | p99 | 84ms | 86ms | 2ms | 2.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.List | avg | 3ms | 1ms | -2ms | -62.20
| CommandWebhookStore.Cleanup | avg | 5ms | 2ms | -3ms | -55.73
| PostStore.SearchPostsForUser | avg | 189ms | 120ms | -69ms | -36.54
| PreferenceStore.DeleteCategoryAndName | avg | 10ms | 7ms | -3ms | -31.08
| ChannelStore.GetTeamChannels | avg | 32ms | 23ms | -9ms | -27.83
| PreferenceStore.Save | avg | 12ms | 10ms | -2ms | -16.80
| ChannelStore.Autocomplete | avg | 42ms | 40ms | -2ms | -4.77
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | p99 | 5ms | 0s | -5ms | -100.50
| UserStore.GetUnreadCountForChannel | p99 | 5ms | 0s | -5ms | -100.27
| PluginStore.List | p99 | 82ms | 8ms | -74ms | -90.23
| PostStore.SearchPostsForUser | p99 | 4.756s | 839ms | -3.917s | -82.35
| PreferenceStore.DeleteCategoryAndName | p99 | 95ms | 25ms | -70ms | -73.68
| ChannelStore.GetChannelsByUser | p99 | 17ms | 5ms | -12ms | -69.77
| ThreadStore.MarkAllAsReadByChannels | p99 | 22ms | 9ms | -13ms | -59.50
| ChannelStore.GetTeamChannels | p99 | 50ms | 25ms | -25ms | -50.50
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.50
| PostStore.Update | p99 | 50ms | 25ms | -25ms | -50.13
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -44.69
| JobStore.Save | p99 | 18ms | 10ms | -8ms | -44.57
| JobStore.UpdateStatus | p99 | 18ms | 10ms | -8ms | -44.20
| UserStore.GetByUsername | p99 | 8ms | 5ms | -3ms | -39.22
| ChannelStore.Autocomplete | p99 | 149ms | 100ms | -49ms | -32.86
| PostAcknowledgementStore.GetForPost | p99 | 14ms | 10ms | -4ms | -28.17
| PreferenceStore.Save | p99 | 44ms | 36ms | -8ms | -18.32
| FileInfoStore.Save | p99 | 19ms | 16ms | -3ms | -16.03
| FileInfoStore.AttachToPost | p99 | 24ms | 21ms | -3ms | -12.71
| UserStore.AutocompleteUsersInChannel | p99 | 380ms | 335ms | -45ms | -11.85
| UserStore.GetUnreadCount | p99 | 614ms | 565ms | -49ms | -7.98
| UserStore.Save | p99 | 153ms | 141ms | -12ms | -7.86
| UserStore.GetAllProfilesInChannel | p99 | 912ms | 881ms | -31ms | -3.40
| ChannelStore.GetMembers | p99 | 249ms | 246ms | -3ms | -1.21
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsers | avg | 6ms | 12ms | 6ms | 108.43
| autocompleteChannelsForTeamForSearch | avg | 285ms | 350ms | 65ms | 22.81
| unfollowThreadByUser | avg | 11ms | 13ms | 2ms | 18.06
| createGroupChannel | avg | 259ms | 283ms | 24ms | 9.26
| updateUserCustomStatus | avg | 144ms | 150ms | 6ms | 4.18
| getProfileImage | avg | 84ms | 87ms | 3ms | 3.56
| addChannelMember | avg | 201ms | 205ms | 4ms | 1.99
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUsers | p99 | 50ms | 228ms | 178ms | 354.98
| getChannel | p99 | 9ms | 26ms | 17ms | 184.72
| deletePost | p99 | 25ms | 47ms | 22ms | 88.52
| logout | p99 | 50ms | 93ms | 43ms | 86.37
| unfollowThreadByUser | p99 | 25ms | 45ms | 20ms | 80.48
| autocompleteChannelsForTeamForSearch | p99 | 2.328s | 3.826s | 1.498s | 64.35
| getChannelMember | p99 | 31ms | 40ms | 9ms | 28.93
| getClientConfig | p99 | 32ms | 35ms | 3ms | 9.38
| getCategoriesForTeamForUser | p99 | 24ms | 26ms | 2ms | 8.31
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPostsForChannel | avg | 36ms | 17ms | -19ms | -52.86
| searchPostsInTeam | avg | 196ms | 124ms | -72ms | -36.76
| createChannel | avg | 33ms | 24ms | -9ms | -27.69
| viewChannel | avg | 14ms | 11ms | -3ms | -21.54
| removeUserCustomStatus | avg | 135ms | 123ms | -12ms | -8.92
| patchPost | avg | 34ms | 31ms | -3ms | -8.85
| createPost | avg | 347ms | 318ms | -29ms | -8.37
| autocompleteUsers | avg | 103ms | 98ms | -5ms | -4.87
| searchAllChannels | avg | 42ms | 40ms | -2ms | -4.75
| createUser | avg | 96ms | 94ms | -2ms | -2.09
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 4.756s | 877ms | -3.879s | -81.56
| patchPost | p99 | 172ms | 50ms | -122ms | -70.93
| getChannelsForUser | p99 | 17ms | 5ms | -12ms | -69.77
| getPostsForChannel | p99 | 314ms | 134ms | -180ms | -57.38
| createChannel | p99 | 50ms | 25ms | -25ms | -50.50
| updateCategoriesForTeamForUser | p99 | 97ms | 50ms | -47ms | -48.45
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -44.69
| createPost | p99 | 1.56s | 997ms | -563ms | -36.08
| searchAllChannels | p99 | 149ms | 100ms | -49ms | -32.86
| viewChannel | p99 | 37ms | 25ms | -12ms | -32.41
| removeUserCustomStatus | p99 | 358ms | 248ms | -110ms | -30.77
| autocompleteUsers | p99 | 335ms | 263ms | -72ms | -21.48
| getTeamsForUser | p99 | 14ms | 12ms | -2ms | -14.79
| getChannelStats | p99 | 190ms | 184ms | -6ms | -3.16
| createDirectChannel | p99 | 485ms | 480ms | -5ms | -1.03
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 69.305
| |  P99| 5ms| 5ms | 0s | 0.000
| BotStore.Save |  Avg| 4ms| 5ms | 1ms | 25.834
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 42ms| 40ms | -2ms | -4.773
| |  P99| 149ms| 100ms | -49ms | -32.857
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 285ms| 350ms | 65ms | 22.813
| |  P99| 2.328s| 3.826s | 1.498s | 64.353
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 22ms | 1ms | 4.662
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 65ms| 66ms | 1ms | 1.538
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.241
| ChannelStore.GetAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.268
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 1ms | -1ms | -53.420
| |  P99| 9ms| 5ms | -4ms | -44.692
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -69.770
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.412
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.572
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 67ms| 66ms | -1ms | -1.503
| |  P99| 244ms| 243ms | -1ms | -0.410
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 77ms| 76ms | -1ms | -1.295
| |  P99| 249ms| 246ms | -3ms | -1.207
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.880
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.771
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.183
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 5ms | -1ms | -18.069
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 32ms| 23ms | -9ms | -27.834
| |  P99| 50ms| 25ms | -25ms | -50.505
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 3ms | 1ms | 40.070
| |  P99| 11ms| 14ms | 3ms | 26.610
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 26ms| 27ms | 1ms | 3.806
| |  P99| 84ms| 86ms | 2ms | 2.392
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.216
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 33ms| 34ms | 1ms | 3.003
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 28ms | 18ms | 182.294
| CommandWebhookStore.Cleanup |  Avg| 5ms| 2ms | -3ms | -55.735
| |  P99| 10ms| 5ms | -5ms | -50.500
| EmojiStore.GetMultipleByName |  Avg| 1ms| 0s | -1ms | -90.257
| |  P99| 5ms| 0s | -5ms | -100.496
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.708
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 39.877
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.027
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.765
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 28.164
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.765
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.804
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 73.729
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 11ms | 6ms | 121.212
| JobStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -44.568
| JobStore.UpdateOptimistically |  Avg| 4ms| 5ms | 1ms | 22.442
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -44.199
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 5ms | 1ms | 23.549
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.516
| PluginStore.List |  Avg| 3ms| 1ms | -2ms | -62.196
| |  P99| 82ms| 8ms | -74ms | -90.235
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.169
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.624
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 3.826s| 3.828s | 2ms | 0.052
| |  P99| 4.975s| 4.975s | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.530
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.622
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 9ms| 8ms | -1ms | -10.777
| |  P99| 25ms| 24ms | -1ms | -4.069
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 42ms| 43ms | 1ms | 2.388
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.868
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 189ms| 120ms | -69ms | -36.544
| |  P99| 4.756s| 839ms | -3.917s | -82.355
| PostStore.SetPostReminder |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.511
| PostStore.Update |  Avg| 20ms| 19ms | -1ms | -5.084
| |  P99| 50ms| 25ms | -25ms | -50.125
| PreferenceStore.DeleteCategoryAndName |  Avg| 10ms| 7ms | -3ms | -31.082
| |  P99| 95ms| 25ms | -70ms | -73.684
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.542
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 10ms | -2ms | -16.798
| |  P99| 44ms| 36ms | -8ms | -18.320
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 42ms| 42ms | 0s | 0.000
| |  P99| 145ms| 149ms | 4ms | 2.759
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.003
| ReactionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 27ms| 31ms | 4ms | 14.786
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 2ms | 1ms | 67.171
| |  P99| 6ms| 7ms | 1ms | 16.357
| SessionStore.Remove |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 2ms | 1ms | 68.046
| |  P99| 9ms| 10ms | 1ms | 10.879
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 33ms| 46ms | 13ms | 39.434
| |  P99| 451ms| 468ms | 17ms | 3.771
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.340
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.955
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.915
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.181
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.486
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 61.463
| TeamStore.SaveMember |  Avg| 68ms| 69ms | 1ms | 1.466
| |  P99| 100ms| 144ms | 44ms | 44.004
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 3ms | 1ms | 40.820
| |  P99| 16ms| 17ms | 1ms | 6.351
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.411
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.407
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.794
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.491
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 3ms | -1ms | -28.510
| |  P99| 22ms| 9ms | -13ms | -59.496
| ThreadStore.MarkAllAsReadByTeam |  Avg| 7ms| 6ms | -1ms | -15.296
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 6ms | 4ms | 199.847
| |  P99| 5ms| 10ms | 5ms | 100.954
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 130ms| 129ms | -1ms | -0.769
| |  P99| 380ms| 335ms | -45ms | -11.852
| UserStore.Count |  Avg| 26ms| 68ms | 42ms | 159.029
| |  P99| 50ms| 99ms | 49ms | 98.554
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.863
| UserStore.GetAllProfiles |  Avg| 4ms| 10ms | 6ms | 152.054
| |  P99| 27ms| 224ms | 197ms | 719.662
| UserStore.GetAllProfilesInChannel |  Avg| 269ms| 269ms | 0s | 0.000
| |  P99| 912ms| 881ms | -31ms | -3.401
| UserStore.GetByUsername |  Avg| 2ms| 1ms | -1ms | -64.519
| |  P99| 8ms| 5ms | -3ms | -39.220
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.842
| UserStore.GetMany |  Avg| 1ms| 2ms | 1ms | 77.166
| |  P99| 5ms| 23ms | 18ms | 363.636
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 614ms| 565ms | -49ms | -7.976
| UserStore.GetUnreadCountForChannel |  Avg| 1ms| 0s | -1ms | -77.138
| |  P99| 5ms| 0s | -5ms | -100.267
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 58.064
| UserStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 153ms| 141ms | -12ms | -7.865
| UserStore.Search |  Avg| 31ms| 30ms | -1ms | -3.211
| |  P99| 244ms| 243ms | -1ms | -0.411
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 130.048
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.467
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.233
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 201ms| 205ms | 4ms | 1.993
| | P99| 477ms| 480ms | 3ms | 0.629
| addTeamMember | Avg| 832ms| 832ms | 0s | 0.000
| | P99| 2.421s| 2.409s | -12ms | -0.496
| autocompleteChannelsForTeamForSearch | Avg| 285ms| 350ms | 65ms | 22.809
| | P99| 2.328s| 3.826s | 1.498s | 64.353
| autocompleteUsers | Avg| 103ms| 98ms | -5ms | -4.873
| | P99| 335ms| 263ms | -72ms | -21.478
| createChannel | Avg| 33ms| 24ms | -9ms | -27.691
| | P99| 50ms| 25ms | -25ms | -50.505
| createDirectChannel | Avg| 191ms| 192ms | 1ms | 0.524
| | P99| 485ms| 480ms | -5ms | -1.031
| createGroupChannel | Avg| 259ms| 283ms | 24ms | 9.259
| | P99| 496ms| 497ms | 1ms | 0.202
| createPost | Avg| 347ms| 318ms | -29ms | -8.367
| | P99| 1.56s| 997ms | -563ms | -36.081
| createUser | Avg| 96ms| 94ms | -2ms | -2.085
| | P99| 243ms| 241ms | -2ms | -0.822
| deletePost | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 47ms | 22ms | 88.523
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 24ms| 26ms | 2ms | 8.307
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 26ms | 17ms | 184.724
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 31ms| 40ms | 9ms | 28.926
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 190ms| 184ms | -6ms | -3.161
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -44.692
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.647
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 5ms | -12ms | -69.770
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 32ms| 35ms | 3ms | 9.384
| getFilePreview | Avg| 33ms| 32ms | -1ms | -3.060
| | P99| 99ms| 98ms | -1ms | -1.013
| getFileThumbnail | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 91ms| 90ms | -1ms | -1.095
| getPostThread | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 36ms| 17ms | -19ms | -52.856
| | P99| 314ms| 134ms | -180ms | -57.378
| getPostsForChannelAroundLastUnread | Avg| 19ms| 18ms | -1ms | -5.219
| | P99| 86ms| 87ms | 1ms | 1.160
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getProfileImage | Avg| 84ms| 87ms | 3ms | 3.563
| | P99| 415ms| 419ms | 4ms | 0.963
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.438
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.859
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 12ms | -2ms | -14.791
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.662
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.244
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 12ms | 6ms | 108.426
| | P99| 50ms| 228ms | 178ms | 354.980
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 62ms| 62ms | 0s | 0.000
| | P99| 246ms| 246ms | 0s | 0.000
| logout | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 50ms| 93ms | 43ms | 86.368
| patchPost | Avg| 34ms| 31ms | -3ms | -8.845
| | P99| 172ms| 50ms | -122ms | -70.935
| removeUserCustomStatus | Avg| 135ms| 123ms | -12ms | -8.919
| | P99| 358ms| 248ms | -110ms | -30.767
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 41ms| 41ms | 0s | 0.000
| searchAllChannels | Avg| 42ms| 40ms | -2ms | -4.747
| | P99| 149ms| 100ms | -49ms | -32.857
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.216
| searchPostsInTeam | Avg| 196ms| 124ms | -72ms | -36.756
| | P99| 4.756s| 877ms | -3.879s | -81.556
| searchUsers | Avg| 32ms| 31ms | -1ms | -3.110
| | P99| 244ms| 244ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 13ms | 2ms | 18.064
| | P99| 25ms| 45ms | 20ms | 80.483
| updateCategoriesForTeamForUser | Avg| 47ms| 46ms | -1ms | -2.148
| | P99| 97ms| 50ms | -47ms | -48.453
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 7ms| 6ms | -1ms | -15.091
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| updateUserCustomStatus | Avg| 144ms| 150ms | 6ms | 4.176
| | P99| 248ms| 248ms | 0s | 0.000
| uploadFileStream | Avg| 420ms| 418ms | -2ms | -0.476
| | P99| 991ms| 985ms | -6ms | -0.605
| viewChannel | Avg| 14ms| 11ms | -3ms | -21.542
| | P99| 37ms| 25ms | -12ms | -32.412
