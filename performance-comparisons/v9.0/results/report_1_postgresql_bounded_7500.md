### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.SearchGroupChannels | avg | 4ms | 12ms | 8ms | 219.98
| RoleStore.ChannelHigherScopedPermissions | avg | 4ms | 13ms | 9ms | 216.70
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 6ms | 4ms | 163.25
| JobStore.GetCountByStatusAndType | avg | 1ms | 3ms | 2ms | 137.78
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 15ms | 34ms | 19ms | 123.76
| SessionStore.GetSessionsExpired | avg | 2ms | 4ms | 2ms | 112.64
| ChannelStore.CreateInitialSidebarCategories | avg | 27ms | 51ms | 24ms | 88.23
| ChannelStore.AutocompleteInTeamForSearch | avg | 54ms | 100ms | 46ms | 85.06
| PostPersistentNotificationStore.Get | avg | 2ms | 4ms | 2ms | 84.35
| ChannelStore.UpdateSidebarCategories | avg | 47ms | 81ms | 34ms | 72.20
| StatusStore.SaveOrUpdate | avg | 47ms | 80ms | 33ms | 70.70
| CommandWebhookStore.Cleanup | avg | 8ms | 13ms | 5ms | 59.87
| ChannelStore.Save | avg | 11ms | 17ms | 6ms | 54.87
| UserStore.Count | avg | 9ms | 13ms | 4ms | 44.66
| ChannelStore.GetSidebarCategory | avg | 13ms | 18ms | 5ms | 39.37
| PostStore.Update | avg | 15ms | 19ms | 4ms | 26.36
| PostStore.Delete | avg | 15ms | 17ms | 2ms | 13.34
| ChannelStore.GetMembers | avg | 111ms | 122ms | 11ms | 9.93
| ChannelStore.CreateDirectChannel | avg | 24ms | 26ms | 2ms | 8.48
| TeamStore.SaveMember | avg | 31ms | 33ms | 2ms | 6.39
| ProductNoticesStore.View | avg | 53ms | 56ms | 3ms | 5.68
| ChannelStore.SaveMember | avg | 36ms | 38ms | 2ms | 5.61
| UserStore.GetAllProfilesInChannel | avg | 269ms | 278ms | 9ms | 3.35
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 246ms | 3.55s | 3.304s | 1344.53
| RoleStore.ChannelHigherScopedPermissions | p99 | 23ms | 225ms | 202ms | 896.63
| PostPersistentNotificationStore.Get | p99 | 9ms | 46ms | 37ms | 397.85
| SessionStore.GetSessionsExpired | p99 | 5ms | 24ms | 19ms | 383.84
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 24ms | 19ms | 383.84
| ChannelStore.Save | p99 | 33ms | 159ms | 126ms | 381.00
| ThreadStore.MarkAllAsReadByChannels | p99 | 10ms | 43ms | 33ms | 343.30
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.GetCountByStatusAndType | p99 | 18ms | 44ms | 26ms | 146.07
| BotStore.Get | p99 | 9ms | 22ms | 13ms | 142.08
| ChannelStore.UpdateSidebarCategories | p99 | 98ms | 235ms | 137ms | 139.32
| PostStore.Update | p99 | 50ms | 110ms | 60ms | 121.19
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 46ms | 24ms | 106.90
| StatusStore.GetByIds | p99 | 18ms | 35ms | 17ms | 96.03
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 89ms | 170ms | 81ms | 91.33
| PostStore.GetPostReminders | p99 | 24ms | 46ms | 22ms | 91.10
| PostStore.Delete | p99 | 25ms | 47ms | 22ms | 88.50
| PluginStore.List | p99 | 22ms | 41ms | 19ms | 85.20
| JobStore.GetNewestJobByStatusesAndType | p99 | 11ms | 20ms | 9ms | 84.91
| LinkMetadataStore.Get | p99 | 11ms | 20ms | 9ms | 79.90
| UserStore.Update | p99 | 47ms | 78ms | 31ms | 65.97
| ChannelStore.SearchGroupChannels | p99 | 28ms | 46ms | 18ms | 63.63
| PostPriorityStore.GetForPosts | p99 | 22ms | 31ms | 9ms | 40.66
| PostStore.GetSingle | p99 | 13ms | 18ms | 5ms | 38.88
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 67ms | 18ms | 36.57
| ThreadStore.Get | p99 | 9ms | 12ms | 3ms | 34.28
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 25ms | 33ms | 8ms | 32.10
| TeamStore.SaveMember | p99 | 127ms | 166ms | 39ms | 30.72
| ChannelStore.CreateInitialSidebarCategories | p99 | 178ms | 229ms | 51ms | 28.59
| PostStore.GetPostIdAfterTime | p99 | 28ms | 36ms | 8ms | 28.33
| JobStore.Get | p99 | 18ms | 23ms | 5ms | 27.40
| UserTermsOfServiceStore.GetByUser | p99 | 30ms | 38ms | 8ms | 27.09
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 27ms | 34ms | 7ms | 26.31
| TeamStore.Get | p99 | 15ms | 19ms | 4ms | 26.30
| UserStore.GetProfileByIds | p99 | 28ms | 35ms | 7ms | 24.79
| ClusterDiscoveryStore.SetLastPingAt | p99 | 45ms | 56ms | 11ms | 24.38
| PostAcknowledgementStore.GetForPosts | p99 | 22ms | 27ms | 5ms | 22.86
| TeamStore.GetTeamsByUserId | p99 | 33ms | 40ms | 7ms | 20.92
| ThreadStore.GetThreadForUser | p99 | 38ms | 46ms | 8ms | 20.90
| ReactionStore.GetForPost | p99 | 19ms | 23ms | 4ms | 20.67
| ProductNoticesStore.View | p99 | 274ms | 329ms | 55ms | 20.05
| StatusStore.Get | p99 | 31ms | 37ms | 6ms | 19.33
| FileInfoStore.AttachToPost | p99 | 47ms | 56ms | 9ms | 19.30
| ChannelStore.GetChannels | p99 | 26ms | 31ms | 5ms | 19.16
| ReactionStore.Save | p99 | 70ms | 83ms | 13ms | 18.57
| ChannelStore.IncrementMentionCount | p99 | 28ms | 33ms | 5ms | 18.04
| ChannelStore.GetPinnedPostCount | p99 | 28ms | 33ms | 5ms | 17.89
| PostStore.GetPosts | p99 | 34ms | 40ms | 6ms | 17.65
| UserStore.GetForLogin | p99 | 35ms | 41ms | 6ms | 17.04
| UserStore.Get | p99 | 18ms | 21ms | 3ms | 16.69
| ThreadStore.GetTotalUnreadThreads | p99 | 30ms | 35ms | 5ms | 16.40
| PostPersistentNotificationStore.GetSingle | p99 | 18ms | 21ms | 3ms | 16.24
| ThreadStore.GetTotalUnreadMentions | p99 | 31ms | 36ms | 5ms | 16.00
| SystemStore.GetByName | p99 | 33ms | 38ms | 5ms | 15.36
| ThreadStore.GetThreadFollowers | p99 | 20ms | 23ms | 3ms | 14.72
| PostStore.GetEtag | p99 | 34ms | 39ms | 5ms | 14.59
| FileInfoStore.GetForPost | p99 | 21ms | 24ms | 3ms | 14.43
| SessionStore.Save | p99 | 56ms | 64ms | 8ms | 14.27
| PostStore.GetPostsBefore | p99 | 28ms | 32ms | 4ms | 14.14
| ChannelStore.GetMembersForUser | p99 | 29ms | 33ms | 4ms | 13.99
| TeamStore.GetAllPage | p99 | 36ms | 41ms | 5ms | 13.91
| ThreadStore.GetTotalThreads | p99 | 31ms | 35ms | 4ms | 13.04
| StatusStore.UpdateLastActivityAt | p99 | 24ms | 27ms | 3ms | 12.64
| ThreadStore.GetTeamsUnreadForUser | p99 | 40ms | 45ms | 5ms | 12.51
| PreferenceStore.Get | p99 | 25ms | 28ms | 3ms | 12.15
| FileInfoStore.Get | p99 | 19ms | 21ms | 2ms | 10.43
| PostAcknowledgementStore.GetForPost | p99 | 20ms | 22ms | 2ms | 10.08
| PostStore.Save | p99 | 81ms | 89ms | 8ms | 9.83
| SessionStore.Get | p99 | 72ms | 79ms | 7ms | 9.69
| ThreadStore.MaintainMembership | p99 | 44ms | 48ms | 4ms | 9.05
| PostPriorityStore.GetForPost | p99 | 22ms | 24ms | 2ms | 8.97
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 34ms | 37ms | 3ms | 8.74
| StatusStore.SaveOrUpdate | p99 | 843ms | 915ms | 72ms | 8.54
| ChannelStore.UpdateLastViewedAt | p99 | 24ms | 26ms | 2ms | 8.37
| GroupStore.GetByName | p99 | 36ms | 39ms | 3ms | 8.32
| ChannelStore.SaveMember | p99 | 212ms | 227ms | 15ms | 7.08
| ChannelStore.GetGuestCount | p99 | 42ms | 45ms | 3ms | 7.08
| UserStore.AutocompleteUsersInChannel | p99 | 263ms | 281ms | 18ms | 6.85
| ChannelStore.GetByName | p99 | 44ms | 47ms | 3ms | 6.78
| ThreadStore.GetThreadsForUser | p99 | 30ms | 32ms | 2ms | 6.64
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 34ms | 36ms | 2ms | 5.86
| ChannelStore.GetMembers | p99 | 429ms | 454ms | 25ms | 5.83
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 145ms | 153ms | 8ms | 5.53
| AuditStore.Save | p99 | 40ms | 42ms | 2ms | 4.98
| PostStore.Get | p99 | 42ms | 44ms | 2ms | 4.73
| PluginStore.SetWithOptions | p99 | 47ms | 49ms | 2ms | 4.29
| UserStore.GetAllProfilesInChannel | p99 | 944ms | 957ms | 13ms | 1.38
| UserStore.Save | p99 | 234ms | 237ms | 3ms | 1.28
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TokenStore.Cleanup | avg | 8ms | 2ms | -6ms | -75.33
| PostStore.AnalyticsPostCount | avg | 833ms | 442ms | -391ms | -46.92
| SessionStore.Remove | avg | 7ms | 4ms | -3ms | -45.57
| PostStore.SetPostReminder | avg | 11ms | 7ms | -4ms | -37.06
| ChannelStore.GetTeamChannels | avg | 18ms | 15ms | -3ms | -16.30
| PreferenceStore.Save | avg | 14ms | 12ms | -2ms | -14.53
| PostStore.SearchPostsForUser | avg | 180ms | 169ms | -11ms | -6.12
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | p99 | 10ms | 0s | -10ms | -103.03
| UserStore.GetUnreadCountForChannel | p99 | 20ms | 0s | -20ms | -100.51
| TokenStore.Cleanup | p99 | 25ms | 5ms | -20ms | -80.97
| SessionStore.Remove | p99 | 24ms | 5ms | -19ms | -78.35
| JobStore.Save | p99 | 77ms | 23ms | -54ms | -70.59
| PostStore.SetPostReminder | p99 | 25ms | 10ms | -15ms | -61.22
| LinkMetadataStore.Save | p99 | 22ms | 9ms | -13ms | -59.50
| PostStore.GetPostReminderMetadata | p99 | 22ms | 9ms | -13ms | -59.39
| PostStore.GetPostsAfter | p99 | 21ms | 9ms | -12ms | -58.11
| PostStore.AnalyticsPostCount | p99 | 995ms | 498ms | -497ms | -49.95
| ChannelStore.GetTeamChannels | p99 | 48ms | 25ms | -23ms | -47.91
| UserStore.GetByUsername | p99 | 32ms | 19ms | -13ms | -40.14
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 16ms | 10ms | -6ms | -36.81
| FileInfoStore.Save | p99 | 44ms | 32ms | -12ms | -27.36
| UserStore.GetUnreadCount | p99 | 31ms | 24ms | -7ms | -22.89
| ChannelStore.CreateDirectChannel | p99 | 189ms | 176ms | -13ms | -6.87
| PreferenceStore.Save | p99 | 89ms | 85ms | -4ms | -4.51
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 31ms | 836ms | 805ms | 2605.26
| searchGroupChannels | avg | 4ms | 12ms | 8ms | 216.37
| getCategoriesForTeamForUser | avg | 16ms | 35ms | 19ms | 121.73
| getChannelMembers | avg | 3ms | 6ms | 3ms | 91.30
| autocompleteChannelsForTeamForSearch | avg | 54ms | 100ms | 46ms | 84.98
| updateCategoriesForTeamForUser | avg | 74ms | 120ms | 46ms | 61.94
| deletePost | avg | 19ms | 22ms | 3ms | 15.50
| createDirectChannel | avg | 263ms | 286ms | 23ms | 8.76
| createGroupChannel | avg | 370ms | 399ms | 29ms | 7.84
| addTeamMember | avg | 889ms | 958ms | 69ms | 7.76
| login | avg | 76ms | 81ms | 5ms | 6.59
| removeUserCustomStatus | avg | 183ms | 195ms | 12ms | 6.56
| updateUserCustomStatus | avg | 210ms | 223ms | 13ms | 6.18
| createPost | avg | 445ms | 466ms | 21ms | 4.72
| addChannelMember | avg | 263ms | 269ms | 6ms | 2.28
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 174ms | 10s | 9.826s | 5662.60
| autocompleteChannelsForTeamForSearch | p99 | 246ms | 3.55s | 3.304s | 1344.53
| getChannelUnread | p99 | 5ms | 20ms | 15ms | 303.03
| unfollowThreadByUser | p99 | 25ms | 82ms | 57ms | 229.38
| getChannel | p99 | 24ms | 77ms | 53ms | 218.70
| getChannelMembers | p99 | 5ms | 10ms | 5ms | 100.90
| getCategoriesForTeamForUser | p99 | 90ms | 175ms | 85ms | 94.51
| updateCategoriesForTeamForUser | p99 | 235ms | 451ms | 216ms | 91.91
| searchGroupChannels | p99 | 28ms | 46ms | 18ms | 63.63
| getUsers | p99 | 59ms | 81ms | 22ms | 37.20
| getUser | p99 | 60ms | 76ms | 16ms | 26.81
| saveReaction | p99 | 150ms | 185ms | 35ms | 23.36
| getTeamsForUser | p99 | 34ms | 40ms | 6ms | 17.42
| getPostThread | p99 | 72ms | 83ms | 11ms | 15.20
| addTeamMember | p99 | 2.493s | 2.869s | 376ms | 15.08
| getTeamsUnreadForUser | p99 | 54ms | 62ms | 8ms | 14.83
| getChannelMembersForTeamForUser | p99 | 35ms | 40ms | 5ms | 14.44
| getChannelsForTeamForUser | p99 | 36ms | 41ms | 5ms | 14.03
| getAllTeams | p99 | 43ms | 48ms | 5ms | 11.70
| getChannelStats | p99 | 65ms | 71ms | 6ms | 9.24
| getUsersByNames | p99 | 24ms | 26ms | 2ms | 8.28
| updateReadStateThreadByUser | p99 | 196ms | 210ms | 14ms | 7.13
| getClientConfig | p99 | 87ms | 93ms | 6ms | 6.88
| getThreadsForUser | p99 | 38ms | 40ms | 2ms | 5.30
| autocompleteUsers | p99 | 220ms | 231ms | 11ms | 4.99
| getPreferences | p99 | 42ms | 44ms | 2ms | 4.77
| login | p99 | 455ms | 471ms | 16ms | 3.52
| getFilePreview | p99 | 152ms | 156ms | 4ms | 2.63
| getChannelMember | p99 | 92ms | 94ms | 2ms | 2.17
| createUser | p99 | 404ms | 410ms | 6ms | 1.48
| getPostsForChannelAroundLastUnread | p99 | 212ms | 215ms | 3ms | 1.42
| createPost | p99 | 2.397s | 2.423s | 26ms | 1.08
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPostsForChannel | avg | 45ms | 24ms | -21ms | -46.72
| createChannel | avg | 19ms | 15ms | -4ms | -21.59
| viewChannel | avg | 14ms | 11ms | -3ms | -21.48
| logout | avg | 62ms | 54ms | -8ms | -12.99
| setPostReminder | avg | 21ms | 19ms | -2ms | -9.54
| searchPostsInTeam | avg | 190ms | 176ms | -14ms | -7.37
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 49ms | 25ms | -24ms | -49.20
| createChannel | p99 | 48ms | 25ms | -23ms | -47.91
| getPostsForChannel | p99 | 426ms | 228ms | -198ms | -46.53
| createDirectChannel | p99 | 623ms | 499ms | -124ms | -19.92
| viewChannel | p99 | 98ms | 90ms | -8ms | -8.18
| updatePreferences | p99 | 50ms | 47ms | -3ms | -6.00
| getPublicChannelsForTeam | p99 | 71ms | 67ms | -4ms | -5.60
| getProfileImage | p99 | 458ms | 448ms | -10ms | -2.19
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 4.981
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 22ms | 13ms | 142.077
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 27ms| 34ms | 7ms | 26.311
| ChannelStore.Autocomplete |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 54ms| 100ms | 46ms | 85.061
| |  P99| 246ms| 3.55s | 3.304s | 1344.527
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 26ms | 2ms | 8.480
| |  P99| 189ms| 176ms | -13ms | -6.869
| ChannelStore.CreateInitialSidebarCategories |  Avg| 27ms| 51ms | 24ms | 88.235
| |  P99| 178ms| 229ms | 51ms | 28.594
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 29ms | 1ms | 3.599
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 145ms| 153ms | 8ms | 5.531
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.780
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 3ms | 1ms | 42.231
| |  P99| 26ms| 31ms | 5ms | 19.156
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 3ms | 1ms | 44.183
| |  P99| 22ms| 23ms | 1ms | 4.587
| ChannelStore.GetFileCount |  Avg| 2ms| 3ms | 1ms | 42.402
| |  P99| 23ms| 24ms | 1ms | 4.259
| ChannelStore.GetGuestCount |  Avg| 3ms| 4ms | 1ms | 29.741
| |  P99| 42ms| 45ms | 3ms | 7.079
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 22ms| 23ms | 1ms | 4.516
| |  P99| 89ms| 90ms | 1ms | 1.121
| ChannelStore.GetMemberForPost |  Avg| 4ms| 5ms | 1ms | 22.225
| |  P99| 23ms| 24ms | 1ms | 4.379
| ChannelStore.GetMembers |  Avg| 111ms| 122ms | 11ms | 9.927
| |  P99| 429ms| 454ms | 25ms | 5.829
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 33ms | 4ms | 13.986
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 33ms | 5ms | 17.891
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 19ms | 1ms | 5.503
| |  P99| 49ms| 67ms | 18ms | 36.573
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 15ms| 34ms | 19ms | 123.755
| |  P99| 89ms| 170ms | 81ms | 91.333
| ChannelStore.GetSidebarCategory |  Avg| 13ms| 18ms | 5ms | 39.372
| |  P99| 80ms| 80ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 18ms| 15ms | -3ms | -16.303
| |  P99| 48ms| 25ms | -23ms | -47.912
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 4ms | 1ms | 30.546
| |  P99| 28ms| 33ms | 5ms | 18.040
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 17ms | 6ms | 54.870
| |  P99| 33ms| 159ms | 126ms | 381.002
| ChannelStore.SaveMember |  Avg| 36ms| 38ms | 2ms | 5.614
| |  P99| 212ms| 227ms | 15ms | 7.083
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 12ms | 8ms | 219.985
| |  P99| 28ms| 46ms | 18ms | 63.625
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.373
| ChannelStore.UpdateSidebarCategories |  Avg| 47ms| 81ms | 34ms | 72.195
| |  P99| 98ms| 235ms | 137ms | 139.322
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.813
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 56ms | 11ms | 24.376
| CommandWebhookStore.Cleanup |  Avg| 8ms| 13ms | 5ms | 59.868
| |  P99| 25ms| 25ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 0s | -1ms | -102.341
| |  P99| 10ms| 0s | -10ms | -103.031
| FileInfoStore.AttachToPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 47ms| 56ms | 9ms | 19.304
| FileInfoStore.Get |  Avg| 1ms| 2ms | 1ms | 69.247
| |  P99| 19ms| 21ms | 2ms | 10.426
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.427
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 32ms | -12ms | -27.363
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 33ms | 8ms | 32.100
| GroupStore.GetByName |  Avg| 2ms| 3ms | 1ms | 43.415
| |  P99| 36ms| 39ms | 3ms | 8.320
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.186
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 23ms | 5ms | 27.397
| JobStore.GetAllByStatus |  Avg| 2ms| 3ms | 1ms | 40.939
| |  P99| 40ms| 41ms | 1ms | 2.498
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 3ms | 2ms | 137.778
| |  P99| 18ms| 44ms | 26ms | 146.067
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 2ms | 1ms | 95.500
| |  P99| 11ms| 20ms | 9ms | 84.906
| JobStore.Save |  Avg| 6ms| 5ms | -1ms | -16.705
| |  P99| 77ms| 23ms | -54ms | -70.588
| JobStore.UpdateOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -19.810
| |  P99| 23ms| 22ms | -1ms | -4.396
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 6ms | 1ms | 21.716
| |  P99| 22ms| 23ms | 1ms | 4.624
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 20ms | 9ms | 79.900
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 9ms | -13ms | -59.495
| PluginStore.Delete |  Avg| 3ms| 4ms | 1ms | 29.344
| |  P99| 24ms| 25ms | 1ms | 4.181
| PluginStore.List |  Avg| 2ms| 3ms | 1ms | 55.080
| |  P99| 22ms| 41ms | 19ms | 85.197
| PluginStore.SetWithOptions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.294
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.081
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 27ms | 5ms | 22.863
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.Get |  Avg| 2ms| 4ms | 2ms | 84.353
| |  P99| 9ms| 46ms | 37ms | 397.849
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 21ms | 3ms | 16.238
| PostPriorityStore.GetForPost |  Avg| 1ms| 2ms | 1ms | 68.240
| |  P99| 22ms| 24ms | 2ms | 8.968
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 31ms | 9ms | 40.661
| PostStore.AnalyticsPostCount |  Avg| 833ms| 442ms | -391ms | -46.921
| |  P99| 995ms| 498ms | -497ms | -49.950
| PostStore.Delete |  Avg| 15ms| 17ms | 2ms | 13.337
| |  P99| 25ms| 47ms | 22ms | 88.499
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 44ms | 2ms | 4.728
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 39ms | 5ms | 14.595
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 4ms | 1ms | 30.058
| |  P99| 28ms| 36ms | 8ms | 28.332
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.296
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 9ms | -13ms | -59.391
| PostStore.GetPostReminders |  Avg| 8ms| 9ms | 1ms | 12.300
| |  P99| 24ms| 46ms | 22ms | 91.097
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 40ms | 6ms | 17.648
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -36.738
| |  P99| 21ms| 9ms | -12ms | -58.106
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 32ms | 4ms | 14.144
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.234
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 78ms| 79ms | 1ms | 1.280
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 38.882
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 16ms | 1ms | 6.520
| |  P99| 81ms| 89ms | 8ms | 9.831
| PostStore.SearchPostsForUser |  Avg| 180ms| 169ms | -11ms | -6.117
| |  P99| 2.339s| 2.32s | -19ms | -0.812
| PostStore.SetPostReminder |  Avg| 11ms| 7ms | -4ms | -37.055
| |  P99| 25ms| 10ms | -15ms | -61.224
| PostStore.Update |  Avg| 15ms| 19ms | 4ms | 26.363
| |  P99| 50ms| 110ms | 60ms | 121.193
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 6ms | 4ms | 163.252
| |  P99| 5ms| 24ms | 19ms | 383.838
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.153
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 41ms | 1ms | 2.498
| PreferenceStore.Save |  Avg| 14ms| 12ms | -2ms | -14.527
| |  P99| 89ms| 85ms | -4ms | -4.509
| ProductNoticesStore.ClearOldNotices |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 53ms| 56ms | 3ms | 5.681
| |  P99| 274ms| 329ms | 55ms | 20.046
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 23ms | 4ms | 20.672
| ReactionStore.Save |  Avg| 13ms| 14ms | 1ms | 7.637
| |  P99| 70ms| 83ms | 13ms | 18.569
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 13ms | 9ms | 216.699
| |  P99| 23ms| 225ms | 202ms | 896.628
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 9ms | 1ms | 12.456
| |  P99| 72ms| 79ms | 7ms | 9.692
| SessionStore.GetSessionsExpired |  Avg| 2ms| 4ms | 2ms | 112.640
| |  P99| 5ms| 24ms | 19ms | 383.838
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| SessionStore.Remove |  Avg| 7ms| 4ms | -3ms | -45.567
| |  P99| 24ms| 5ms | -19ms | -78.351
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 56ms| 64ms | 8ms | 14.267
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.276
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 37ms | 6ms | 19.330
| StatusStore.GetByIds |  Avg| 1ms| 2ms | 1ms | 68.852
| |  P99| 18ms| 35ms | 17ms | 96.031
| StatusStore.SaveOrUpdate |  Avg| 47ms| 80ms | 33ms | 70.696
| |  P99| 843ms| 915ms | 72ms | 8.540
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 4ms | 1ms | 30.173
| |  P99| 22ms| 46ms | 24ms | 106.904
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.641
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 38ms | 5ms | 15.363
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 19ms | 4ms | 26.305
| TeamStore.GetAllPage |  Avg| 2ms| 3ms | 1ms | 42.384
| |  P99| 36ms| 41ms | 5ms | 13.906
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.905
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 37ms | 3ms | 8.736
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.667
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 40ms | 7ms | 20.925
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.689
| TeamStore.SaveMember |  Avg| 31ms| 33ms | 2ms | 6.390
| |  P99| 127ms| 166ms | 39ms | 30.716
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 34.285
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.310
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 45ms | 5ms | 12.514
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 2ms | 1ms | 69.685
| |  P99| 20ms| 23ms | 3ms | 14.724
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 46ms | 8ms | 20.896
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 32ms | 2ms | 6.645
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 35ms | 4ms | 13.042
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 36ms | 5ms | 16.002
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 35ms | 5ms | 16.403
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 36ms | 2ms | 5.859
| ThreadStore.MaintainMembership |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 44ms| 48ms | 4ms | 9.045
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 43ms | 33ms | 343.301
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.550
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.586
| TokenStore.Cleanup |  Avg| 8ms| 2ms | -6ms | -75.332
| |  P99| 25ms| 5ms | -20ms | -80.971
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 263ms| 281ms | 18ms | 6.848
| UserStore.Count |  Avg| 9ms| 13ms | 4ms | 44.658
| |  P99| 24ms| 25ms | 1ms | 4.255
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 21ms | 3ms | 16.691
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 269ms| 278ms | 9ms | 3.346
| |  P99| 944ms| 957ms | 13ms | 1.377
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 19ms | -13ms | -40.143
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 41ms | 6ms | 17.041
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 35ms | 7ms | 24.785
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.187
| UserStore.GetUnreadCount |  Avg| 2ms| 3ms | 1ms | 40.654
| |  P99| 31ms| 24ms | -7ms | -22.892
| UserStore.GetUnreadCountForChannel |  Avg| 1ms| 0s | -1ms | -68.273
| |  P99| 20ms| 0s | -20ms | -100.508
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.Save |  Avg| 76ms| 77ms | 1ms | 1.312
| |  P99| 234ms| 237ms | 3ms | 1.281
| UserStore.Search |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 9ms| 10ms | 1ms | 11.195
| |  P99| 47ms| 78ms | 31ms | 65.973
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 43ms | -1ms | -2.284
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 35ms| 35ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 38ms | 8ms | 27.090
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 263ms| 269ms | 6ms | 2.281
| | P99| 499ms| 496ms | -3ms | -0.601
| addTeamMember | Avg| 889ms| 958ms | 69ms | 7.764
| | P99| 2.493s| 2.869s | 376ms | 15.083
| autocompleteChannelsForTeamForSearch | Avg| 54ms| 100ms | 46ms | 84.979
| | P99| 246ms| 3.55s | 3.304s | 1344.527
| autocompleteUsers | Avg| 39ms| 40ms | 1ms | 2.547
| | P99| 220ms| 231ms | 11ms | 4.994
| createChannel | Avg| 19ms| 15ms | -4ms | -21.593
| | P99| 48ms| 25ms | -23ms | -47.912
| createDirectChannel | Avg| 263ms| 286ms | 23ms | 8.761
| | P99| 623ms| 499ms | -124ms | -19.915
| createGroupChannel | Avg| 370ms| 399ms | 29ms | 7.841
| | P99| 969ms| 975ms | 6ms | 0.619
| createPost | Avg| 445ms| 466ms | 21ms | 4.719
| | P99| 2.397s| 2.423s | 26ms | 1.085
| createUser | Avg| 111ms| 111ms | 0s | 0.000
| | P99| 404ms| 410ms | 6ms | 1.485
| deletePost | Avg| 19ms| 22ms | 3ms | 15.496
| | P99| 48ms| 49ms | 1ms | 2.105
| followThreadByUser | Avg| 13ms| 14ms | 1ms | 7.535
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 4ms | 1ms | 32.373
| | P99| 43ms| 48ms | 5ms | 11.697
| getCategoriesForTeamForUser | Avg| 16ms| 35ms | 19ms | 121.732
| | P99| 90ms| 175ms | 85ms | 94.513
| getChannel | Avg| 5ms| 6ms | 1ms | 21.031
| | P99| 24ms| 77ms | 53ms | 218.696
| getChannelMember | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 92ms| 94ms | 2ms | 2.166
| getChannelMembers | Avg| 3ms| 6ms | 3ms | 91.301
| | P99| 5ms| 10ms | 5ms | 100.904
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 35ms| 40ms | 5ms | 14.445
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 65ms| 71ms | 6ms | 9.242
| getChannelUnread | Avg| 1ms| 2ms | 1ms | 67.435
| | P99| 5ms| 20ms | 15ms | 303.030
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 36ms| 41ms | 5ms | 14.029
| getChannelsForUser | Avg| 2ms| 3ms | 1ms | 43.201
| | P99| 22ms| 23ms | 1ms | 4.587
| getClientConfig | Avg| 10ms| 11ms | 1ms | 10.006
| | P99| 87ms| 93ms | 6ms | 6.882
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 152ms| 156ms | 4ms | 2.625
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 98ms| 99ms | 1ms | 1.022
| getPostThread | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 72ms| 83ms | 11ms | 15.203
| getPostsForChannel | Avg| 45ms| 24ms | -21ms | -46.716
| | P99| 426ms| 228ms | -198ms | -46.528
| getPostsForChannelAroundLastUnread | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 212ms| 215ms | 3ms | 1.416
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 42ms| 44ms | 2ms | 4.770
| getProfileImage | Avg| 88ms| 87ms | -1ms | -1.138
| | P99| 458ms| 448ms | -10ms | -2.185
| getPublicChannelsForTeam | Avg| 19ms| 20ms | 1ms | 5.145
| | P99| 71ms| 67ms | -4ms | -5.595
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 40ms | 6ms | 17.418
| getTeamsUnreadForUser | Avg| 5ms| 6ms | 1ms | 19.396
| | P99| 54ms| 62ms | 8ms | 14.826
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 40ms | 2ms | 5.297
| getUser | Avg| 4ms| 5ms | 1ms | 24.650
| | P99| 60ms| 76ms | 16ms | 26.806
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 59ms| 81ms | 22ms | 37.204
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 26ms | 2ms | 8.279
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 76ms| 81ms | 5ms | 6.592
| | P99| 455ms| 471ms | 16ms | 3.516
| logout | Avg| 62ms| 54ms | -8ms | -12.986
| | P99| 235ms| 233ms | -2ms | -0.851
| patchPost | Avg| 31ms| 836ms | 805ms | 2605.262
| | P99| 174ms| 10s | 9.826s | 5662.604
| removeUserCustomStatus | Avg| 183ms| 195ms | 12ms | 6.565
| | P99| 488ms| 490ms | 2ms | 0.410
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 23ms| 24ms | 1ms | 4.418
| | P99| 150ms| 185ms | 35ms | 23.362
| searchAllChannels | Avg| 45ms| 45ms | 0s | 0.000
| | P99| 100ms| 100ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 12ms | 8ms | 216.368
| | P99| 28ms| 46ms | 18ms | 63.625
| searchPostsInTeam | Avg| 190ms| 176ms | -14ms | -7.373
| | P99| 2.365s| 2.345s | -20ms | -0.846
| searchUsers | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 21ms| 19ms | -2ms | -9.542
| | P99| 49ms| 25ms | -24ms | -49.196
| unfollowThreadByUser | Avg| 14ms| 15ms | 1ms | 7.322
| | P99| 25ms| 82ms | 57ms | 229.384
| updateCategoriesForTeamForUser | Avg| 74ms| 120ms | 46ms | 61.944
| | P99| 235ms| 451ms | 216ms | 91.913
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 50ms| 47ms | -3ms | -6.001
| updateReadStateThreadByUser | Avg| 37ms| 38ms | 1ms | 2.677
| | P99| 196ms| 210ms | 14ms | 7.129
| updateUserCustomStatus | Avg| 210ms| 223ms | 13ms | 6.181
| | P99| 492ms| 493ms | 1ms | 0.203
| uploadFileStream | Avg| 434ms| 434ms | 0s | 0.000
| | P99| 990ms| 990ms | 0s | 0.000
| viewChannel | Avg| 14ms| 11ms | -3ms | -21.478
| | P99| 98ms| 90ms | -8ms | -8.182
