### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 6ms | 6ms | 2554523.09
| PostStore.AnalyticsPostCount | avg | 1ms | 13ms | 12ms | 891.00
| StatusStore.SaveOrUpdate | avg | 18ms | 45ms | 27ms | 146.31
| PluginStore.List | avg | 1ms | 3ms | 2ms | 133.65
| UserStore.GetProfilesNotInChannel | avg | 4ms | 7ms | 3ms | 67.29
| ChannelStore.Save | avg | 9ms | 13ms | 4ms | 43.00
| ChannelStore.GetTeamChannels | avg | 14ms | 19ms | 5ms | 35.23
| PostStore.SetPostReminder | avg | 6ms | 8ms | 2ms | 31.17
| PostStore.SearchPostsForUser | avg | 155ms | 196ms | 41ms | 26.40
| TeamStore.GetTotalMemberCount | avg | 25ms | 30ms | 5ms | 19.95
| ChannelStore.CreateDirectChannel | avg | 18ms | 21ms | 3ms | 16.57
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 78ms | 73ms | 1474.75
| PostStore.AnalyticsPostCount | p99 | 5ms | 25ms | 20ms | 403.80
| PluginStore.List | p99 | 8ms | 41ms | 33ms | 402.44
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 24ms | 19ms | 383.84
| PostStore.SetPostReminder | p99 | 10ms | 45ms | 35ms | 351.76
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| ChannelStore.GetTeamChannels | p99 | 25ms | 96ms | 71ms | 285.71
| ThreadStore.Get | p99 | 5ms | 18ms | 13ms | 262.63
| StatusStore.GetByIds | p99 | 5ms | 18ms | 13ms | 261.17
| PostStore.GetPostReminderMetadata | p99 | 23ms | 82ms | 59ms | 255.96
| ChannelStore.Save | p99 | 24ms | 82ms | 58ms | 244.33
| ChannelStore.CreateDirectChannel | p99 | 44ms | 132ms | 88ms | 200.00
| JobStore.UpdateStatusOptimistically | p99 | 8ms | 22ms | 14ms | 177.39
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 24ms | 14ms | 140.67
| ChannelStore.UpdateSidebarCategories | p99 | 98ms | 223ms | 125ms | 127.55
| StatusStore.SaveOrUpdate | p99 | 238ms | 484ms | 246ms | 103.37
| JobStore.UpdateStatus | p99 | 9ms | 18ms | 9ms | 96.95
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 17ms | 8ms | 94.04
| UserStore.Count | p99 | 25ms | 46ms | 21ms | 84.51
| LinkMetadataStore.Save | p99 | 5ms | 9ms | 4ms | 80.81
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 10ms | 17ms | 7ms | 70.41
| JobStore.GetAllByStatus | p99 | 25ms | 41ms | 16ms | 64.92
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 41ms | 16ms | 64.03
| ChannelStore.GetChannelsByUser | p99 | 14ms | 21ms | 7ms | 49.29
| UserStore.Update | p99 | 15ms | 21ms | 6ms | 40.21
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 32ms | 44ms | 12ms | 37.11
| EmojiStore.GetByName | p99 | 11ms | 15ms | 4ms | 35.69
| UserStore.GetUnreadCount | p99 | 18ms | 23ms | 5ms | 27.30
| TeamStore.GetMember | p99 | 8ms | 10ms | 2ms | 26.15
| ClusterDiscoveryStore.SetLastPingAt | p99 | 28ms | 35ms | 7ms | 25.23
| PostStore.GetPosts | p99 | 25ms | 31ms | 6ms | 24.23
| ThreadStore.MaintainMembership | p99 | 31ms | 38ms | 7ms | 22.89
| DraftStore.GetDraftsForUser | p99 | 21ms | 25ms | 4ms | 19.03
| ChannelStore.GetAllChannelMembersForUser | p99 | 25ms | 29ms | 4ms | 15.73
| TeamStore.GetTeamsForUser | p99 | 28ms | 32ms | 4ms | 14.26
| UserStore.Get | p99 | 14ms | 16ms | 2ms | 14.08
| TeamStore.GetTeamsByUserId | p99 | 29ms | 33ms | 4ms | 13.83
| StatusStore.UpdateLastActivityAt | p99 | 20ms | 22ms | 2ms | 10.14
| PostAcknowledgementStore.GetForPosts | p99 | 21ms | 23ms | 2ms | 9.34
| JobStore.GetNewestJobByStatusesAndType | p99 | 22ms | 24ms | 2ms | 9.28
| PostStore.GetPostsByThread | p99 | 22ms | 24ms | 2ms | 9.05
| PostStore.Get | p99 | 34ms | 37ms | 3ms | 8.95
| PostStore.GetPostReminders | p99 | 22ms | 24ms | 2ms | 8.91
| PostStore.GetPostIdAfterTime | p99 | 24ms | 26ms | 2ms | 8.29
| SessionStore.Get | p99 | 60ms | 65ms | 5ms | 8.27
| SessionStore.GetLRUSessions | p99 | 25ms | 27ms | 2ms | 8.15
| ChannelStore.GetMember | p99 | 37ms | 40ms | 3ms | 8.05
| ChannelStore.Get | p99 | 25ms | 27ms | 2ms | 8.05
| ChannelStore.GetMemberCount | p99 | 80ms | 86ms | 6ms | 7.50
| SystemStore.GetByName | p99 | 27ms | 29ms | 2ms | 7.30
| ThreadStore.GetThreadForUser | p99 | 29ms | 31ms | 2ms | 6.91
| FileInfoStore.AttachToPost | p99 | 29ms | 31ms | 2ms | 6.85
| PostStore.GetPostsSince | p99 | 70ms | 73ms | 3ms | 4.29
| ChannelStore.SaveMember | p99 | 196ms | 202ms | 6ms | 3.06
| PostStore.SearchPostsForUser | p99 | 2.295s | 2.354s | 59ms | 2.57
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 88ms | 90ms | 2ms | 2.26
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | avg | 4ms | 1ms | -3ms | -83.42
| UserStore.GetProfilesInChannel | avg | 159ms | 56ms | -103ms | -64.94
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 25ms | 19ms | -6ms | -23.97
| ChannelStore.GetSidebarCategory | avg | 10ms | 8ms | -2ms | -20.83
| ChannelStore.AutocompleteInTeamForSearch | avg | 21ms | 19ms | -2ms | -9.51
| ChannelStore.UpdateSidebarCategories | avg | 47ms | 45ms | -2ms | -4.22
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetCountByStatusAndType | p99 | 61ms | 9ms | -52ms | -85.25
| PostPersistentNotificationStore.Get | p99 | 21ms | 5ms | -16ms | -76.92
| PostAcknowledgementStore.GetForPost | p99 | 23ms | 9ms | -14ms | -60.44
| PostPersistentNotificationStore.DeleteExpired | p99 | 21ms | 9ms | -12ms | -57.69
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 25ms | -25ms | -50.25
| PostStore.GetSingle | p99 | 14ms | 9ms | -5ms | -36.12
| ReactionStore.GetForPost | p99 | 22ms | 15ms | -7ms | -31.54
| ChannelStore.AutocompleteInTeamForSearch | p99 | 112ms | 77ms | -35ms | -31.39
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 296ms | 205ms | -91ms | -30.72
| LinkMetadataStore.Get | p99 | 16ms | 11ms | -5ms | -30.47
| ThreadStore.UpdateMembership | p99 | 13ms | 10ms | -3ms | -23.32
| RoleStore.ChannelHigherScopedPermissions | p99 | 23ms | 18ms | -5ms | -22.11
| TeamStore.Get | p99 | 16ms | 13ms | -3ms | -18.99
| PostStore.Update | p99 | 53ms | 44ms | -9ms | -17.14
| PostPriorityStore.GetForPost | p99 | 23ms | 20ms | -3ms | -12.95
| FileInfoStore.GetByIds | p99 | 23ms | 20ms | -3ms | -12.87
| UserStore.UpdateUpdateAt | p99 | 29ms | 26ms | -3ms | -10.39
| ChannelStore.GetFileCount | p99 | 23ms | 21ms | -2ms | -8.82
| FileInfoStore.SetContent | p99 | 47ms | 43ms | -4ms | -8.55
| GroupStore.GetByName | p99 | 35ms | 32ms | -3ms | -8.52
| ThreadStore.GetTeamsUnreadForUser | p99 | 38ms | 35ms | -3ms | -7.99
| TeamStore.SaveMember | p99 | 108ms | 100ms | -8ms | -7.43
| PluginStore.SetWithOptions | p99 | 43ms | 40ms | -3ms | -7.01
| UserStore.GetProfilesInChannel | p99 | 248ms | 244ms | -4ms | -1.61
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | avg | 5ms | 11ms | 6ms | 122.53
| login | avg | 90ms | 171ms | 81ms | 89.78
| setPostReminder | avg | 15ms | 19ms | 4ms | 26.47
| searchPostsInTeam | avg | 165ms | 202ms | 37ms | 22.44
| createChannel | avg | 299ms | 347ms | 48ms | 16.04
| logout | avg | 45ms | 50ms | 5ms | 11.15
| createDirectChannel | avg | 295ms | 314ms | 19ms | 6.44
| removeUserCustomStatus | avg | 192ms | 200ms | 8ms | 4.16
| createUser | avg | 163ms | 168ms | 5ms | 3.07
| addChannelMember | avg | 257ms | 260ms | 3ms | 1.17
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | p99 | 5ms | 25ms | 20ms | 403.55
| setPostReminder | p99 | 25ms | 90ms | 65ms | 261.57
| updateCategoriesForTeamForUser | p99 | 100ms | 223ms | 123ms | 123.62
| createChannel | p99 | 498ms | 960ms | 462ms | 92.86
| logout | p99 | 50ms | 96ms | 46ms | 92.46
| getChannel | p99 | 36ms | 65ms | 29ms | 80.56
| createDirectChannel | p99 | 500ms | 767ms | 267ms | 53.44
| login | p99 | 493ms | 751ms | 258ms | 52.37
| getPostThread | p99 | 54ms | 70ms | 16ms | 29.45
| getTeamMember | p99 | 19ms | 22ms | 3ms | 16.00
| getDrafts | p99 | 22ms | 25ms | 3ms | 13.57
| getTeamsForUser | p99 | 31ms | 35ms | 4ms | 12.83
| createUser | p99 | 616ms | 665ms | 49ms | 7.96
| getPublicChannelsForTeam | p99 | 41ms | 44ms | 3ms | 7.33
| getTeamMembersForUser | p99 | 43ms | 46ms | 3ms | 7.05
| getThreadsForUser | p99 | 30ms | 32ms | 2ms | 6.67
| getChannelMembersForTeamForUser | p99 | 32ms | 34ms | 2ms | 6.26
| getPostsForChannelAroundLastUnread | p99 | 189ms | 195ms | 6ms | 3.17
| viewChannel | p99 | 73ms | 75ms | 2ms | 2.73
| autocompleteUsers | p99 | 247ms | 253ms | 6ms | 2.43
| getCategoriesForTeamForUser | p99 | 91ms | 93ms | 2ms | 2.19
| searchPostsInTeam | p99 | 2.33s | 2.364s | 34ms | 1.46
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getFilteredUsersStats | avg | 13ms | 0s | -13ms | -100.67
| saveReaction | avg | 9ms | 0s | -9ms | -100.52
| patchPost | avg | 37ms | 27ms | -10ms | -26.73
| getAnalytics | avg | 27ms | 23ms | -4ms | -14.68
| autocompleteChannelsForTeamForSearch | avg | 21ms | 19ms | -2ms | -9.48
| createCategoryForTeamForUser | avg | 28ms | 26ms | -2ms | -7.19
| getTeamStats | avg | 55ms | 52ms | -3ms | -5.49
| getProfileImage | avg | 83ms | 79ms | -4ms | -4.85
| createPost | avg | 328ms | 323ms | -5ms | -1.53
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateUserCustomStatus | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getFilteredUsersStats | p99 | 25ms | 0s | -25ms | -100.60
| saveReaction | p99 | 57ms | 0s | -57ms | -100.34
| patchPost | p99 | 1.09s | 267ms | -823ms | -75.51
| autocompleteChannelsForTeamForSearch | p99 | 146ms | 77ms | -69ms | -47.22
| createGroupChannel | p99 | 1.435s | 989ms | -446ms | -31.08
| getUsers | p99 | 65ms | 58ms | -7ms | -10.82
| upsertDraft | p99 | 30ms | 27ms | -3ms | -9.94
| getUser | p99 | 57ms | 53ms | -4ms | -7.04
| getFilePreview | p99 | 190ms | 184ms | -6ms | -3.16
| createPost | p99 | 1.773s | 1.723s | -50ms | -2.82
| updateReadStateThreadByUser | p99 | 158ms | 154ms | -4ms | -2.53
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 74.709
| |  P99| 5ms| 22ms | 17ms | 343.434
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 73ms| 72ms | -1ms | -1.378
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 8ms| 9ms | 1ms | 12.519
| |  P99| 10ms| 24ms | 14ms | 140.673
| ChannelStore.Autocomplete |  Avg| 44ms| 45ms | 1ms | 2.299
| |  P99| 99ms| 99ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 21ms| 19ms | -2ms | -9.510
| |  P99| 112ms| 77ms | -35ms | -31.389
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 21ms | 3ms | 16.570
| |  P99| 44ms| 132ms | 88ms | 200.001
| ChannelStore.CreateInitialSidebarCategories |  Avg| 24ms| 23ms | -1ms | -4.218
| |  P99| 180ms| 179ms | -1ms | -0.557
| ChannelStore.CreateSidebarCategory |  Avg| 26ms| 25ms | -1ms | -3.814
| |  P99| 50ms| 25ms | -25ms | -50.251
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.046
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 12ms| 13ms | 1ms | 8.161
| |  P99| 32ms| 44ms | 12ms | 37.112
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 6ms | 1ms | 18.487
| |  P99| 25ms| 29ms | 4ms | 15.731
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 25ms| 19ms | -6ms | -23.974
| |  P99| 296ms| 205ms | -91ms | -30.720
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 3ms | 1ms | 46.957
| |  P99| 14ms| 21ms | 7ms | 49.294
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.817
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 40ms | 3ms | 8.050
| ChannelStore.GetMemberCount |  Avg| 21ms| 22ms | 1ms | 4.774
| |  P99| 80ms| 86ms | 6ms | 7.500
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.812
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 94.039
| ChannelStore.GetPublicChannelsForTeam |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 25ms| 41ms | 16ms | 64.026
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 16ms| 17ms | 1ms | 6.114
| |  P99| 88ms| 90ms | 2ms | 2.265
| ChannelStore.GetSidebarCategory |  Avg| 10ms| 8ms | -2ms | -20.832
| |  P99| 42ms| 41ms | -1ms | -2.381
| ChannelStore.GetTeamChannels |  Avg| 14ms| 19ms | 5ms | 35.231
| |  P99| 25ms| 96ms | 71ms | 285.714
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 13ms | 4ms | 42.998
| |  P99| 24ms| 82ms | 58ms | 244.332
| ChannelStore.SaveMember |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 196ms| 202ms | 6ms | 3.062
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.150
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 47ms| 45ms | -2ms | -4.222
| |  P99| 98ms| 223ms | 125ms | 127.547
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.491
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 35ms | 7ms | 25.227
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.628
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.646
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.178
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.653
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 25ms | 4ms | 19.035
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.156
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 15ms | 4ms | 35.691
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 6.854
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.258
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.869
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.537
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.295
| FileInfoStore.Search |  Avg| 4ms| 1ms | -3ms | -83.421
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.582
| |  P99| 47ms| 43ms | -4ms | -8.546
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.348
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 35ms| 32ms | -3ms | -8.524
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 1ms | -1ms | -65.624
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 1ms | -1ms | -55.827
| |  P99| 16ms| 16ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 41ms | 16ms | 64.924
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -40.818
| |  P99| 61ms| 9ms | -52ms | -85.246
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.281
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.348
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.101
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 96.948
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 5ms | 1ms | 25.923
| |  P99| 8ms| 22ms | 14ms | 177.389
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -30.472
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.359
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 3ms | 2ms | 133.650
| |  P99| 8ms| 41ms | 33ms | 402.439
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -14.935
| |  P99| 43ms| 40ms | -3ms | -7.009
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -59.281
| |  P99| 23ms| 9ms | -14ms | -60.441
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.336
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -57.692
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.923
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.017
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.952
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.368
| PostStore.AnalyticsPostCount |  Avg| 1ms| 13ms | 12ms | 891.004
| |  P99| 5ms| 25ms | 20ms | 403.801
| PostStore.Delete |  Avg| 13ms| 12ms | -1ms | -7.966
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 37ms | 3ms | 8.946
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.067
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.291
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.985
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 4ms | 1ms | 36.900
| |  P99| 23ms| 82ms | 59ms | 255.963
| PostStore.GetPostReminders |  Avg| 6ms| 7ms | 1ms | 15.730
| |  P99| 22ms| 24ms | 2ms | 8.909
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 31ms | 6ms | 24.226
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 4ms | 1ms | 28.884
| |  P99| 23ms| 24ms | 1ms | 4.315
| PostStore.GetPostsByThread |  Avg| 4ms| 5ms | 1ms | 23.494
| |  P99| 22ms| 24ms | 2ms | 9.050
| PostStore.GetPostsSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 70ms| 73ms | 3ms | 4.290
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -36.123
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.353
| PostStore.SearchPostsForUser |  Avg| 155ms| 196ms | 41ms | 26.404
| |  P99| 2.295s| 2.354s | 59ms | 2.571
| PostStore.SetPostReminder |  Avg| 6ms| 8ms | 2ms | 31.170
| |  P99| 10ms| 45ms | 35ms | 351.759
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 53ms| 44ms | -9ms | -17.142
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 84ms| 83ms | -1ms | -1.188
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 229ms| 230ms | 1ms | 0.437
| ReactionStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -38.652
| |  P99| 22ms| 15ms | -7ms | -31.542
| RetentionPolicyStore.GetAll |  Avg| 2ms| 1ms | -1ms | -56.619
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -131.570
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 18ms | -5ms | -22.111
| RoleStore.GetByNames |  Avg| 0s| 6ms | 6ms | 2554523.088
| |  P99| 5ms| 78ms | 73ms | 1474.746
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 60ms| 65ms | 5ms | 8.275
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.148
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 2ms | 1ms | 69.218
| |  P99| 10ms| 17ms | 7ms | 70.413
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.914
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.083
| StatusStore.GetByIds |  Avg| 1ms| 2ms | 1ms | 79.821
| |  P99| 5ms| 18ms | 13ms | 261.171
| StatusStore.SaveOrUpdate |  Avg| 18ms| 45ms | 27ms | 146.309
| |  P99| 238ms| 484ms | 246ms | 103.372
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.139
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 29ms | 2ms | 7.296
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.993
| TeamStore.GetActiveMemberCount |  Avg| 51ms| 50ms | -1ms | -1.973
| |  P99| 100ms| 99ms | -1ms | -1.005
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 31ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.856
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 26.153
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 3ms | 1ms | 40.870
| |  P99| 29ms| 33ms | 4ms | 13.828
| TeamStore.GetTeamsForUser |  Avg| 2ms| 3ms | 1ms | 41.319
| |  P99| 28ms| 32ms | 4ms | 14.261
| TeamStore.GetTotalMemberCount |  Avg| 25ms| 30ms | 5ms | 19.955
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 108ms| 100ms | -8ms | -7.429
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 4ms | 1ms | 29.182
| |  P99| 38ms| 35ms | -3ms | -7.990
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 2ms | 1ms | 68.796
| |  P99| 20ms| 21ms | 1ms | 4.988
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 6.909
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.079
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 4ms | 1ms | 28.911
| |  P99| 23ms| 24ms | 1ms | 4.331
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.144
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 3ms | 1ms | 40.783
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.167
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 38ms | 7ms | 22.887
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.770
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -23.318
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -61.679
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 48ms| 48ms | 0s | 0.000
| |  P99| 308ms| 310ms | 2ms | 0.650
| UserStore.Count |  Avg| 13ms| 14ms | 1ms | 7.808
| |  P99| 25ms| 46ms | 21ms | 84.507
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.079
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 251ms| 251ms | 0s | 0.000
| |  P99| 909ms| 908ms | -1ms | -0.110
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 29ms | -1ms | -3.301
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.027
| UserStore.GetProfilesInChannel |  Avg| 159ms| 56ms | -103ms | -64.937
| |  P99| 248ms| 244ms | -4ms | -1.611
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 7ms | 3ms | 67.286
| |  P99| 5ms| 24ms | 19ms | 383.838
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 23ms | 5ms | 27.302
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.Save |  Avg| 73ms| 73ms | 0s | 0.000
| |  P99| 225ms| 223ms | -2ms | -0.889
| UserStore.Search |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 40.207
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.623
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.095
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 29ms| 26ms | -3ms | -10.390
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 37ms| 36ms | -1ms | -2.673
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 257ms| 260ms | 3ms | 1.168
| | P99| 496ms| 499ms | 3ms | 0.605
| addTeamMember | Avg| 884ms| 890ms | 6ms | 0.679
| | P99| 2.487s| 2.491s | 4ms | 0.161
| autocompleteChannelsForTeamForSearch | Avg| 21ms| 19ms | -2ms | -9.482
| | P99| 146ms| 77ms | -69ms | -47.220
| autocompleteUsers | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 247ms| 253ms | 6ms | 2.425
| createCategoryForTeamForUser | Avg| 28ms| 26ms | -2ms | -7.195
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 299ms| 347ms | 48ms | 16.037
| | P99| 498ms| 960ms | 462ms | 92.864
| createDirectChannel | Avg| 295ms| 314ms | 19ms | 6.440
| | P99| 500ms| 767ms | 267ms | 53.437
| createGroupChannel | Avg| 465ms| 461ms | -4ms | -0.861
| | P99| 1.435s| 989ms | -446ms | -31.078
| createPost | Avg| 328ms| 323ms | -5ms | -1.527
| | P99| 1.773s| 1.723s | -50ms | -2.819
| createUser | Avg| 163ms| 168ms | 5ms | 3.072
| | P99| 616ms| 665ms | 49ms | 7.957
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.112
| deletePost | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 12ms | 1ms | 8.751
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 41ms| 40ms | -1ms | -2.450
| getAnalytics | Avg| 27ms| 23ms | -4ms | -14.679
| | P99| 50ms| 49ms | -1ms | -2.016
| getCategoriesForTeamForUser | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 91ms| 93ms | 2ms | 2.194
| getChannel | Avg| 6ms| 7ms | 1ms | 16.590
| | P99| 36ms| 65ms | 29ms | 80.555
| getChannelMember | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 99ms| 100ms | 1ms | 1.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 32ms| 34ms | 2ms | 6.256
| getChannelMembersForUser | Avg| 8ms| 7ms | -1ms | -12.927
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.078
| getChannelUnread | Avg| 1ms| 2ms | 1ms | 79.254
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 35ms| 36ms | 1ms | 2.865
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 86ms| 86ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 3ms | 1ms | 40.963
| | P99| 22ms| 25ms | 3ms | 13.570
| getFilePreview | Avg| 42ms| 41ms | -1ms | -2.398
| | P99| 190ms| 184ms | -6ms | -3.157
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFilteredUsersStats | Avg| 13ms| 0s | -13ms | -100.666
| | P99| 25ms| 0s | -25ms | -100.604
| getGroups | Avg| 1ms| 2ms | 1ms | 70.024
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 0s | -1ms | -68.196
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 7ms| 8ms | 1ms | 13.829
| | P99| 54ms| 70ms | 16ms | 29.454
| getPostsForChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 199ms| 198ms | -1ms | -0.503
| getPostsForChannelAroundLastUnread | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 189ms| 195ms | 6ms | 3.175
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 40ms| 40ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 0s | -1ms | -70.594
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 83ms| 79ms | -4ms | -4.846
| | P99| 387ms| 388ms | 1ms | 0.258
| getPublicChannelsForTeam | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 41ms| 44ms | 3ms | 7.332
| getRolesByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 3ms | 1ms | 40.910
| | P99| 19ms| 22ms | 3ms | 16.005
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 43ms| 46ms | 3ms | 7.045
| getTeamStats | Avg| 55ms| 52ms | -3ms | -5.491
| | P99| 100ms| 99ms | -1ms | -1.005
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 35ms | 4ms | 12.828
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -1.999
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 30ms| 32ms | 2ms | 6.675
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 57ms| 53ms | -4ms | -7.039
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 65ms| 58ms | -7ms | -10.823
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 90ms| 171ms | 81ms | 89.780
| | P99| 493ms| 751ms | 258ms | 52.367
| logout | Avg| 45ms| 50ms | 5ms | 11.153
| | P99| 50ms| 96ms | 46ms | 92.462
| patchPost | Avg| 37ms| 27ms | -10ms | -26.727
| | P99| 1.09s| 267ms | -823ms | -75.512
| removeUserCustomStatus | Avg| 192ms| 200ms | 8ms | 4.157
| | P99| 486ms| 486ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 0s | -9ms | -100.524
| | P99| 57ms| 0s | -57ms | -100.340
| searchAllChannels | Avg| 44ms| 45ms | 1ms | 2.285
| | P99| 99ms| 99ms | 0s | 0.000
| searchFiles | Avg| 5ms| 11ms | 6ms | 122.528
| | P99| 5ms| 25ms | 20ms | 403.550
| searchGroupChannels | Avg| 3ms| 4ms | 1ms | 29.293
| | P99| 24ms| 25ms | 1ms | 4.150
| searchPostsInTeam | Avg| 165ms| 202ms | 37ms | 22.439
| | P99| 2.33s| 2.364s | 34ms | 1.459
| searchUsers | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 19ms | 4ms | 26.469
| | P99| 25ms| 90ms | 65ms | 261.569
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 64ms| 63ms | -1ms | -1.564
| | P99| 100ms| 223ms | 123ms | 123.618
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 27ms| 26ms | -1ms | -3.697
| updateReadStateAllThreadsByUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 37ms| 38ms | 1ms | 2.689
| | P99| 158ms| 154ms | -4ms | -2.534
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| uploadFileStream | Avg| 382ms| 379ms | -3ms | -0.785
| | P99| 992ms| 989ms | -3ms | -0.302
| upsertDraft | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 30ms| 27ms | -3ms | -9.939
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 73ms| 75ms | 2ms | 2.733
