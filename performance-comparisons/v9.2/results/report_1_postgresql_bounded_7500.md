### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 4ms | 27ms | 23ms | 559.07
| PreferenceStore.DeleteCategoryAndName | avg | 2ms | 5ms | 3ms | 141.07
| PostStore.GetPostsAfter | avg | 3ms | 6ms | 3ms | 91.75
| ThreadStore.MarkAllAsReadByTeam | avg | 2ms | 4ms | 2ms | 82.52
| PostStore.AnalyticsPostCount | avg | 445ms | 803ms | 358ms | 80.47
| PostStore.GetPostReminders | avg | 8ms | 11ms | 3ms | 39.03
| ChannelStore.CreateDirectChannel | avg | 23ms | 25ms | 2ms | 8.64
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 41ms | 459ms | 418ms | 1021.25
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 24ms | 19ms | 383.61
| PostStore.GetPostsAfter | p99 | 19ms | 45ms | 26ms | 134.27
| PostPriorityStore.GetForPost | p99 | 24ms | 53ms | 29ms | 123.33
| BotStore.Get | p99 | 22ms | 46ms | 24ms | 106.90
| PostStore.AnalyticsPostCount | p99 | 498ms | 995ms | 497ms | 99.90
| ChannelStore.GetPublicChannelsForTeam | p99 | 46ms | 81ms | 35ms | 75.36
| ChannelStore.AutocompleteInTeamForSearch | p99 | 86ms | 144ms | 58ms | 67.24
| FileInfoStore.SetContent | p99 | 56ms | 82ms | 26ms | 46.22
| ThreadStore.Get | p99 | 14ms | 20ms | 6ms | 43.64
| StatusStore.GetByIds | p99 | 38ms | 45ms | 7ms | 18.57
| FileInfoStore.Save | p99 | 38ms | 43ms | 5ms | 13.09
| ThreadStore.GetThreadFollowers | p99 | 29ms | 31ms | 2ms | 6.88
| RoleStore.ChannelHigherScopedPermissions | p99 | 76ms | 79ms | 3ms | 3.92
| ChannelStore.Save | p99 | 83ms | 86ms | 3ms | 3.60
| ThreadStore.GetTeamsUnreadForUser | p99 | 57ms | 59ms | 2ms | 3.52
| UserStore.Update | p99 | 62ms | 64ms | 2ms | 3.23
| ChannelStore.GetMembers | p99 | 484ms | 491ms | 7ms | 1.45
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | avg | 2ms | 0s | -2ms | -125.46
| PostPersistentNotificationStore.UpdateLastActivity | avg | 2ms | 0s | -2ms | -84.06
| UserAccessTokenStore.GetByToken | avg | 8ms | 2ms | -6ms | -73.01
| ChannelStore.SearchGroupChannels | avg | 13ms | 5ms | -8ms | -61.12
| SessionStore.Remove | avg | 4ms | 2ms | -2ms | -55.20
| ChannelStore.CreateInitialSidebarCategories | avg | 47ms | 24ms | -23ms | -48.64
| ChannelStore.UpdateSidebarCategories | avg | 64ms | 34ms | -30ms | -47.09
| ChannelStore.AutocompleteInTeamForSearch | avg | 45ms | 25ms | -20ms | -44.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 39ms | 22ms | -17ms | -43.62
| ChannelStore.GetSidebarCategory | avg | 19ms | 11ms | -8ms | -41.94
| ChannelStore.GetChannelUnread | avg | 5ms | 3ms | -2ms | -37.54
| PostStore.SetPostReminder | avg | 6ms | 4ms | -2ms | -30.88
| RoleStore.ChannelHigherScopedPermissions | avg | 12ms | 10ms | -2ms | -16.23
| ProductNoticesStore.View | avg | 46ms | 42ms | -4ms | -8.65
| PostStore.SearchPostsForUser | avg | 176ms | 161ms | -15ms | -8.53
| ChannelStore.SaveMember | avg | 42ms | 39ms | -3ms | -7.19
| ChannelStore.GetMembers | avg | 130ms | 124ms | -6ms | -4.61
| UserStore.AutocompleteUsersInChannel | avg | 52ms | 50ms | -2ms | -3.88
| UserStore.GetAllProfilesInChannel | avg | 300ms | 293ms | -7ms | -2.33
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| UserAccessTokenStore.GetByToken | p99 | 48ms | 8ms | -40ms | -83.11
| PostStore.SetPostReminder | p99 | 47ms | 9ms | -38ms | -80.85
| LinkMetadataStore.Save | p99 | 22ms | 5ms | -17ms | -78.34
| ThreadStore.MarkAllAsReadByChannels | p99 | 40ms | 9ms | -31ms | -77.02
| PostPersistentNotificationStore.DeleteExpired | p99 | 21ms | 5ms | -16ms | -76.92
| SessionStore.Remove | p99 | 22ms | 5ms | -17ms | -75.72
| PostPersistentNotificationStore.Get | p99 | 20ms | 5ms | -15ms | -75.38
| JobStore.UpdateStatus | p99 | 22ms | 8ms | -14ms | -64.97
| JobStore.UpdateStatusOptimistically | p99 | 22ms | 9ms | -13ms | -60.32
| ChannelStore.UpdateSidebarCategories | p99 | 99ms | 50ms | -49ms | -49.28
| JobStore.GetNewestJobByStatusesAndType | p99 | 51ms | 26ms | -25ms | -49.02
| ChannelStore.GetChannelUnread | p99 | 45ms | 23ms | -22ms | -48.75
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 24ms | -22ms | -48.09
| PostStore.GetPostReminderMetadata | p99 | 44ms | 24ms | -20ms | -45.71
| PostStore.Update | p99 | 92ms | 50ms | -42ms | -45.65
| JobStore.UpdateOptimistically | p99 | 9ms | 5ms | -4ms | -45.20
| JobStore.GetCountByStatusAndType | p99 | 38ms | 21ms | -17ms | -45.03
| JobStore.Save | p99 | 38ms | 21ms | -17ms | -44.74
| ChannelStore.GetChannelsByUser | p99 | 78ms | 45ms | -33ms | -42.31
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 17ms | 10ms | -7ms | -41.07
| TeamStore.GetMember | p99 | 13ms | 8ms | -5ms | -38.08
| ChannelStore.GetFileCount | p99 | 40ms | 27ms | -13ms | -32.52
| PostStore.Get | p99 | 70ms | 49ms | -21ms | -30.03
| TeamStore.GetByName | p99 | 44ms | 31ms | -13ms | -29.30
| PostStore.GetPostsByThread | p99 | 35ms | 25ms | -10ms | -28.94
| ThreadStore.GetThreadUnreadReplyCount | p99 | 34ms | 25ms | -9ms | -26.47
| StatusStore.UpdateLastActivityAt | p99 | 34ms | 25ms | -9ms | -26.40
| PluginStore.SetWithOptions | p99 | 74ms | 55ms | -19ms | -25.84
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 207ms | 154ms | -53ms | -25.56
| PluginStore.Delete | p99 | 36ms | 28ms | -8ms | -22.38
| JobStore.Get | p99 | 22ms | 18ms | -4ms | -18.56
| PreferenceStore.Save | p99 | 158ms | 130ms | -28ms | -17.72
| LinkMetadataStore.Get | p99 | 29ms | 24ms | -5ms | -17.06
| UserStore.AutocompleteUsersInChannel | p99 | 325ms | 272ms | -53ms | -16.30
| ThreadStore.GetMembershipForUser | p99 | 31ms | 26ms | -5ms | -16.14
| ReactionStore.GetForPost | p99 | 37ms | 31ms | -6ms | -16.03
| UserStore.Get | p99 | 25ms | 21ms | -4ms | -16.01
| ThreadStore.MaintainMembership | p99 | 58ms | 49ms | -9ms | -15.55
| PostStore.GetPostIdBeforeTime | p99 | 34ms | 29ms | -5ms | -14.88
| ChannelStore.UpdateLastViewedAt | p99 | 35ms | 30ms | -5ms | -14.45
| ChannelStore.GetSidebarCategory | p99 | 91ms | 78ms | -13ms | -14.29
| SessionStore.UpdateLastActivityAt | p99 | 30ms | 26ms | -4ms | -13.34
| UserStore.GetProfilesByUsernames | p99 | 39ms | 34ms | -5ms | -12.80
| ChannelStore.SearchGroupChannels | p99 | 55ms | 48ms | -7ms | -12.71
| ProductNoticesStore.View | p99 | 461ms | 403ms | -58ms | -12.59
| TeamStore.Get | p99 | 27ms | 24ms | -3ms | -11.02
| GroupStore.GetByName | p99 | 50ms | 45ms | -5ms | -10.05
| UserStore.GetUnreadCount | p99 | 40ms | 36ms | -4ms | -9.93
| PostStore.GetPostsBefore | p99 | 43ms | 39ms | -4ms | -9.39
| PreferenceStore.GetAll | p99 | 54ms | 49ms | -5ms | -9.27
| ReactionStore.Save | p99 | 98ms | 89ms | -9ms | -9.17
| PostStore.GetPostIdAfterTime | p99 | 44ms | 40ms | -4ms | -9.14
| UserStore.UpdateUpdateAt | p99 | 44ms | 40ms | -4ms | -9.10
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 46ms | 42ms | -4ms | -8.76
| AuditStore.Save | p99 | 48ms | 44ms | -4ms | -8.41
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 36ms | 33ms | -3ms | -8.24
| PostStore.GetSingle | p99 | 25ms | 23ms | -2ms | -7.98
| ChannelStore.Autocomplete | p99 | 166ms | 153ms | -13ms | -7.85
| ChannelStore.CreateDirectChannel | p99 | 214ms | 198ms | -16ms | -7.48
| ChannelStore.CreateInitialSidebarCategories | p99 | 244ms | 226ms | -18ms | -7.39
| PreferenceStore.Get | p99 | 41ms | 38ms | -3ms | -7.34
| ChannelStore.GetPinnedPostCount | p99 | 42ms | 39ms | -3ms | -7.15
| SessionStore.Save | p99 | 87ms | 81ms | -6ms | -6.92
| PostAcknowledgementStore.GetForPosts | p99 | 44ms | 41ms | -3ms | -6.86
| ChannelStore.Get | p99 | 44ms | 41ms | -3ms | -6.77
| SystemStore.GetByName | p99 | 45ms | 42ms | -3ms | -6.71
| UserStore.GetProfileByIds | p99 | 45ms | 42ms | -3ms | -6.62
| ThreadStore.GetTotalUnreadThreads | p99 | 45ms | 42ms | -3ms | -6.62
| ChannelStore.SaveMember | p99 | 259ms | 242ms | -17ms | -6.56
| ThreadStore.GetTotalThreads | p99 | 46ms | 43ms | -3ms | -6.54
| StatusStore.Get | p99 | 46ms | 43ms | -3ms | -6.51
| PostStore.GetEtag | p99 | 46ms | 43ms | -3ms | -6.51
| ClusterDiscoveryStore.SetLastPingAt | p99 | 46ms | 43ms | -3ms | -6.51
| PostPriorityStore.GetForPosts | p99 | 46ms | 43ms | -3ms | -6.50
| TeamStore.GetTeamsForUser | p99 | 49ms | 46ms | -3ms | -6.13
| TeamStore.SaveMember | p99 | 202ms | 190ms | -12ms | -5.93
| SessionStore.Get | p99 | 92ms | 87ms | -5ms | -5.44
| UserStore.GetAllProfiles | p99 | 38ms | 36ms | -2ms | -5.23
| PostStore.Save | p99 | 97ms | 92ms | -5ms | -5.15
| ChannelStore.IncrementMentionCount | p99 | 40ms | 38ms | -2ms | -4.94
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 41ms | 39ms | -2ms | -4.91
| ChannelStore.GetMembersForUser | p99 | 43ms | 41ms | -2ms | -4.68
| ThreadStore.GetTotalUnreadMentions | p99 | 45ms | 43ms | -2ms | -4.44
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 46ms | 44ms | -2ms | -4.34
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 187ms | 179ms | -8ms | -4.28
| PostStore.GetPosts | p99 | 47ms | 45ms | -2ms | -4.27
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 47ms | 45ms | -2ms | -4.27
| UserStore.GetForLogin | p99 | 47ms | 45ms | -2ms | -4.23
| TeamStore.GetAllPage | p99 | 48ms | 46ms | -2ms | -4.21
| UserStore.UpdateFailedPasswordAttempts | p99 | 49ms | 47ms | -2ms | -4.09
| ThreadStore.GetThreadForUser | p99 | 50ms | 48ms | -2ms | -4.02
| PostStore.SearchPostsForUser | p99 | 2.368s | 2.313s | -55ms | -2.32
| UserStore.Save | p99 | 243ms | 240ms | -3ms | -1.23
| UserStore.GetAllProfilesInChannel | p99 | 997ms | 987ms | -10ms | -1.00
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 40ms | 381ms | 341ms | 859.24
| getChannel | avg | 6ms | 8ms | 2ms | 31.43
| followThreadByUser | avg | 17ms | 21ms | 4ms | 23.04
| uploadFileStream | avg | 465ms | 480ms | 15ms | 3.23
| removeUserCustomStatus | avg | 208ms | 214ms | 6ms | 2.88
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | p99 | 499ms | 955ms | 456ms | 91.32
| getPublicChannelsForTeam | p99 | 48ms | 81ms | 33ms | 69.03
| autocompleteChannelsForTeamForSearch | p99 | 86ms | 144ms | 58ms | 67.24
| getChannel | p99 | 43ms | 69ms | 26ms | 60.12
| unfollowThreadByUser | p99 | 25ms | 38ms | 13ms | 52.48
| removeUserCustomStatus | p99 | 492ms | 670ms | 178ms | 36.18
| uploadFileStream | p99 | 1.596s | 1.973s | 377ms | 23.62
| getFileThumbnail | p99 | 159ms | 165ms | 6ms | 3.78
| followThreadByUser | p99 | 94ms | 96ms | 2ms | 2.12
| logout | p99 | 237ms | 240ms | 3ms | 1.26
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchGroupChannels | avg | 13ms | 5ms | -8ms | -60.80
| getChannelUnread | avg | 7ms | 4ms | -3ms | -45.62
| setPostReminder | avg | 27ms | 15ms | -12ms | -45.23
| autocompleteChannelsForTeamForSearch | avg | 45ms | 25ms | -20ms | -44.10
| getCategoriesForTeamForUser | avg | 39ms | 22ms | -17ms | -43.19
| updateCategoriesForTeamForUser | avg | 104ms | 59ms | -45ms | -43.13
| getChannelsForUser | avg | 9ms | 6ms | -3ms | -32.19
| deletePost | avg | 19ms | 16ms | -3ms | -15.85
| logout | avg | 66ms | 60ms | -6ms | -9.07
| searchPostsInTeam | avg | 190ms | 173ms | -17ms | -8.95
| getPostsForChannel | avg | 34ms | 32ms | -2ms | -5.94
| addTeamMember | avg | 1.036s | 979ms | -57ms | -5.50
| addChannelMember | avg | 263ms | 249ms | -14ms | -5.33
| autocompleteUsers | avg | 41ms | 39ms | -2ms | -4.88
| createDirectChannel | avg | 293ms | 280ms | -13ms | -4.44
| createGroupChannel | avg | 414ms | 396ms | -18ms | -4.35
| createPost | avg | 572ms | 551ms | -21ms | -3.67
| login | avg | 85ms | 82ms | -3ms | -3.53
| createUser | avg | 118ms | 114ms | -4ms | -3.39
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelsForUser | p99 | 280ms | 45ms | -235ms | -83.92
| setPostReminder | p99 | 97ms | 25ms | -72ms | -74.23
| getChannelUnread | p99 | 81ms | 23ms | -58ms | -72.05
| deletePost | p99 | 49ms | 25ms | -24ms | -49.23
| getTeamMember | p99 | 30ms | 23ms | -7ms | -23.12
| viewChannel | p99 | 138ms | 107ms | -31ms | -22.54
| getCategoriesForTeamForUser | p99 | 210ms | 164ms | -46ms | -21.90
| login | p99 | 635ms | 500ms | -135ms | -21.25
| getClientConfig | p99 | 125ms | 99ms | -26ms | -20.72
| getChannelMember | p99 | 165ms | 135ms | -30ms | -18.18
| getAllTeams | p99 | 61ms | 50ms | -11ms | -18.10
| getPostThread | p99 | 150ms | 126ms | -24ms | -15.96
| searchGroupChannels | p99 | 55ms | 48ms | -7ms | -12.71
| getPostsForChannel | p99 | 278ms | 248ms | -30ms | -10.79
| updateCategoriesForTeamForUser | p99 | 243ms | 217ms | -26ms | -10.69
| getUsersByNames | p99 | 40ms | 36ms | -4ms | -10.04
| getTeamMembersForUser | p99 | 75ms | 68ms | -7ms | -9.28
| addTeamMember | p99 | 4.472s | 4.069s | -403ms | -9.01
| autocompleteUsers | p99 | 249ms | 227ms | -22ms | -8.82
| getPreferences | p99 | 60ms | 55ms | -5ms | -8.29
| createDirectChannel | p99 | 742ms | 688ms | -54ms | -7.28
| updateReadStateThreadByUser | p99 | 247ms | 229ms | -18ms | -7.28
| saveReaction | p99 | 208ms | 195ms | -13ms | -6.25
| updatePreferences | p99 | 48ms | 45ms | -3ms | -6.20
| createUser | p99 | 487ms | 462ms | -25ms | -5.14
| getTeamsUnreadForUser | p99 | 87ms | 83ms | -4ms | -4.61
| getThreadsForUser | p99 | 49ms | 47ms | -2ms | -4.11
| getUsers | p99 | 95ms | 93ms | -2ms | -2.09
| searchAllChannels | p99 | 166ms | 164ms | -2ms | -1.21
| searchPostsInTeam | p99 | 2.379s | 2.353s | -26ms | -1.09
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 44ms | -4ms | -8.406
| BotStore.Get |  Avg| 3ms| 4ms | 1ms | 31.840
| |  P99| 22ms| 46ms | 24ms | 106.904
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 39ms | -2ms | -4.907
| ChannelStore.Autocomplete |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 166ms| 153ms | -13ms | -7.847
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 45ms| 25ms | -20ms | -44.166
| |  P99| 86ms| 144ms | 58ms | 67.244
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 25ms | 2ms | 8.636
| |  P99| 214ms| 198ms | -16ms | -7.477
| ChannelStore.CreateInitialSidebarCategories |  Avg| 47ms| 24ms | -23ms | -48.636
| |  P99| 244ms| 226ms | -18ms | -7.390
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 41ms | -3ms | -6.767
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.778
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 30ms| 29ms | -1ms | -3.375
| |  P99| 187ms| 179ms | -8ms | -4.282
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 5ms| 3ms | -2ms | -37.543
| |  P99| 45ms| 23ms | -22ms | -48.753
| ChannelStore.GetChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.384
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -69.550
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 78ms| 45ms | -33ms | -42.308
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 33ms | -3ms | -8.239
| ChannelStore.GetFileCount |  Avg| 4ms| 3ms | -1ms | -26.276
| |  P99| 40ms| 27ms | -13ms | -32.524
| ChannelStore.GetGuestCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.198
| ChannelStore.GetMemberCount |  Avg| 25ms| 24ms | -1ms | -4.005
| |  P99| 96ms| 95ms | -1ms | -1.043
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 27ms| 28ms | 1ms | 3.697
| ChannelStore.GetMembers |  Avg| 130ms| 124ms | -6ms | -4.613
| |  P99| 484ms| 491ms | 7ms | 1.448
| ChannelStore.GetMembersForUser |  Avg| 5ms| 4ms | -1ms | -21.928
| |  P99| 43ms| 41ms | -2ms | -4.680
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 39ms | -3ms | -7.155
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 20ms | 1ms | 5.311
| |  P99| 46ms| 81ms | 35ms | 75.361
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 39ms| 22ms | -17ms | -43.616
| |  P99| 207ms| 154ms | -53ms | -25.562
| ChannelStore.GetSidebarCategory |  Avg| 19ms| 11ms | -8ms | -41.942
| |  P99| 91ms| 78ms | -13ms | -14.286
| ChannelStore.GetTeamChannels |  Avg| 15ms| 16ms | 1ms | 6.618
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 38ms | -2ms | -4.943
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 12ms | 1ms | 9.259
| |  P99| 83ms| 86ms | 3ms | 3.604
| ChannelStore.SaveMember |  Avg| 42ms| 39ms | -3ms | -7.195
| |  P99| 259ms| 242ms | -17ms | -6.557
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 5ms | -8ms | -61.122
| |  P99| 55ms| 48ms | -7ms | -12.713
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 30ms | -5ms | -14.448
| ChannelStore.UpdateSidebarCategories |  Avg| 64ms| 34ms | -30ms | -47.085
| |  P99| 99ms| 50ms | -49ms | -49.277
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -41.073
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 4ms | -1ms | -18.715
| |  P99| 46ms| 43ms | -3ms | -6.508
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -14.933
| |  P99| 48ms| 47ms | -1ms | -2.078
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 43ms | 5ms | 13.085
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 56ms| 82ms | 26ms | 46.222
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 3ms | -1ms | -27.132
| |  P99| 46ms| 42ms | -4ms | -8.760
| GroupStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 50ms| 45ms | -5ms | -10.047
| GroupStore.GetGroups |  Avg| 4ms| 3ms | -1ms | -28.545
| |  P99| 38ms| 37ms | -1ms | -2.628
| JobStore.Get |  Avg| 3ms| 2ms | -1ms | -38.211
| |  P99| 22ms| 18ms | -4ms | -18.561
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 21ms | -17ms | -45.033
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -32.648
| |  P99| 51ms| 26ms | -25ms | -49.020
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -24.275
| |  P99| 38ms| 21ms | -17ms | -44.737
| JobStore.UpdateOptimistically |  Avg| 3ms| 2ms | -1ms | -36.721
| |  P99| 9ms| 5ms | -4ms | -45.198
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -27.338
| |  P99| 22ms| 8ms | -14ms | -64.965
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -26.609
| |  P99| 22ms| 9ms | -13ms | -60.325
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 29ms| 24ms | -5ms | -17.060
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -78.342
| PluginStore.Delete |  Avg| 3ms| 2ms | -1ms | -36.927
| |  P99| 36ms| 28ms | -8ms | -22.384
| PluginStore.List |  Avg| 3ms| 4ms | 1ms | 38.886
| |  P99| 41ms| 41ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -15.018
| |  P99| 74ms| 55ms | -19ms | -25.838
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.667
| PostAcknowledgementStore.GetForPosts |  Avg| 4ms| 3ms | -1ms | -27.426
| |  P99| 44ms| 41ms | -3ms | -6.856
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.923
| PostPersistentNotificationStore.Get |  Avg| 2ms| 1ms | -1ms | -50.883
| |  P99| 20ms| 5ms | -15ms | -75.377
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.137
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 2ms| 0s | -2ms | -84.061
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 38.711
| |  P99| 24ms| 53ms | 29ms | 123.327
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.498
| PostStore.AnalyticsPostCount |  Avg| 445ms| 803ms | 358ms | 80.468
| |  P99| 498ms| 995ms | 497ms | 99.899
| PostStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 49ms | -21ms | -30.027
| PostStore.GetEtag |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.510
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 40ms | -4ms | -9.143
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 29ms | -5ms | -14.877
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 44ms| 24ms | -20ms | -45.714
| PostStore.GetPostReminders |  Avg| 8ms| 11ms | 3ms | 39.034
| |  P99| 92ms| 92ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 5ms | -1ms | -17.821
| |  P99| 47ms| 45ms | -2ms | -4.274
| PostStore.GetPostsAfter |  Avg| 3ms| 6ms | 3ms | 91.753
| |  P99| 19ms| 45ms | 26ms | 134.269
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 39ms | -4ms | -9.391
| PostStore.GetPostsByIds |  Avg| 2ms| 0s | -2ms | -125.465
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 25ms | -10ms | -28.943
| PostStore.GetPostsSince |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.163
| PostStore.GetSingle |  Avg| 3ms| 2ms | -1ms | -39.608
| |  P99| 25ms| 23ms | -2ms | -7.980
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 97ms| 92ms | -5ms | -5.155
| PostStore.SearchPostsForUser |  Avg| 176ms| 161ms | -15ms | -8.532
| |  P99| 2.368s| 2.313s | -55ms | -2.322
| PostStore.SetPostReminder |  Avg| 6ms| 4ms | -2ms | -30.878
| |  P99| 47ms| 9ms | -38ms | -80.851
| PostStore.Update |  Avg| 13ms| 12ms | -1ms | -7.497
| |  P99| 92ms| 50ms | -42ms | -45.655
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 5ms | 3ms | 141.074
| |  P99| 5ms| 24ms | 19ms | 383.614
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 38ms | -3ms | -7.335
| PreferenceStore.GetAll |  Avg| 6ms| 5ms | -1ms | -17.751
| |  P99| 54ms| 49ms | -5ms | -9.272
| PreferenceStore.Save |  Avg| 12ms| 11ms | -1ms | -8.538
| |  P99| 158ms| 130ms | -28ms | -17.718
| ProductNoticesStore.ClearOldNotices |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 46ms| 42ms | -4ms | -8.650
| |  P99| 461ms| 403ms | -58ms | -12.591
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 31ms | -6ms | -16.029
| ReactionStore.Save |  Avg| 10ms| 9ms | -1ms | -10.127
| |  P99| 98ms| 89ms | -9ms | -9.172
| RoleStore.ChannelHigherScopedPermissions |  Avg| 12ms| 10ms | -2ms | -16.234
| |  P99| 76ms| 79ms | 3ms | 3.922
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 92ms| 87ms | -5ms | -5.436
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 2ms | -2ms | -55.203
| |  P99| 22ms| 5ms | -17ms | -75.724
| SessionStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 81ms | -6ms | -6.923
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 26ms | -4ms | -13.335
| StatusStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.511
| StatusStore.GetByIds |  Avg| 3ms| 4ms | 1ms | 31.762
| |  P99| 38ms| 45ms | 7ms | 18.574
| StatusStore.SaveOrUpdate |  Avg| 4ms| 27ms | 23ms | 559.072
| |  P99| 41ms| 459ms | 418ms | 1021.253
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 46ms| 24ms | -22ms | -48.087
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 25ms | -9ms | -26.398
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 42ms | -3ms | -6.708
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 27ms| 24ms | -3ms | -11.024
| TeamStore.GetAllPage |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.205
| TeamStore.GetByName |  Avg| 3ms| 2ms | -1ms | -33.583
| |  P99| 44ms| 31ms | -13ms | -29.296
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.268
| TeamStore.GetMany |  Avg| 1ms| 0s | -1ms | -75.392
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 8ms | -5ms | -38.080
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 46ms | -3ms | -6.127
| TeamStore.SaveMember |  Avg| 32ms| 31ms | -1ms | -3.079
| |  P99| 202ms| 190ms | -12ms | -5.929
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 20ms | 6ms | 43.639
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 26ms | -5ms | -16.137
| ThreadStore.GetTeamsUnreadForUser |  Avg| 6ms| 5ms | -1ms | -17.975
| |  P99| 57ms| 59ms | 2ms | 3.523
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 31ms | 2ms | 6.880
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 48ms | -2ms | -4.024
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 5ms | -1ms | -17.880
| |  P99| 34ms| 25ms | -9ms | -26.471
| ThreadStore.GetThreadsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.406
| ThreadStore.GetTotalThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.541
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.443
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 42ms | -3ms | -6.624
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.337
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 58ms| 49ms | -9ms | -15.553
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -28.806
| |  P99| 40ms| 9ms | -31ms | -77.024
| ThreadStore.MarkAllAsReadByTeam |  Avg| 2ms| 4ms | 2ms | 82.517
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.479
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 8ms| 2ms | -6ms | -73.008
| |  P99| 48ms| 8ms | -40ms | -83.110
| UserStore.AutocompleteUsersInChannel |  Avg| 52ms| 50ms | -2ms | -3.878
| |  P99| 325ms| 272ms | -53ms | -16.299
| UserStore.Count |  Avg| 14ms| 13ms | -1ms | -7.207
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 21ms | -4ms | -16.012
| UserStore.GetAllProfiles |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.234
| UserStore.GetAllProfilesInChannel |  Avg| 300ms| 293ms | -7ms | -2.335
| |  P99| 997ms| 987ms | -10ms | -1.003
| UserStore.GetByUsername |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.235
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.231
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 42ms | -3ms | -6.624
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 34ms | -5ms | -12.795
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 36ms | -4ms | -9.927
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.Save |  Avg| 78ms| 77ms | -1ms | -1.280
| |  P99| 243ms| 240ms | -3ms | -1.233
| UserStore.Search |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Update |  Avg| 8ms| 7ms | -1ms | -12.502
| |  P99| 62ms| 64ms | 2ms | 3.235
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 5ms | -1ms | -17.818
| |  P99| 49ms| 47ms | -2ms | -4.093
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 40ms | -4ms | -9.102
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.205
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 51ms| 50ms | -1ms | -1.973
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 263ms| 249ms | -14ms | -5.325
| | P99| 499ms| 955ms | 456ms | 91.316
| addTeamMember | Avg| 1.036s| 979ms | -57ms | -5.503
| | P99| 4.472s| 4.069s | -403ms | -9.011
| autocompleteChannelsForTeamForSearch | Avg| 45ms| 25ms | -20ms | -44.104
| | P99| 86ms| 144ms | 58ms | 67.244
| autocompleteUsers | Avg| 41ms| 39ms | -2ms | -4.883
| | P99| 249ms| 227ms | -22ms | -8.818
| createChannel | Avg| 15ms| 16ms | 1ms | 6.567
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 293ms| 280ms | -13ms | -4.443
| | P99| 742ms| 688ms | -54ms | -7.281
| createGroupChannel | Avg| 414ms| 396ms | -18ms | -4.352
| | P99| 979ms| 972ms | -7ms | -0.715
| createPost | Avg| 572ms| 551ms | -21ms | -3.672
| | P99| 2.46s| 2.438s | -22ms | -0.894
| createUser | Avg| 118ms| 114ms | -4ms | -3.389
| | P99| 487ms| 462ms | -25ms | -5.139
| deletePost | Avg| 19ms| 16ms | -3ms | -15.849
| | P99| 49ms| 25ms | -24ms | -49.231
| followThreadByUser | Avg| 17ms| 21ms | 4ms | 23.037
| | P99| 94ms| 96ms | 2ms | 2.116
| getAllTeams | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 61ms| 50ms | -11ms | -18.104
| getCategoriesForTeamForUser | Avg| 39ms| 22ms | -17ms | -43.187
| | P99| 210ms| 164ms | -46ms | -21.903
| getChannel | Avg| 6ms| 8ms | 2ms | 31.427
| | P99| 43ms| 69ms | 26ms | 60.117
| getChannelMember | Avg| 13ms| 12ms | -1ms | -7.952
| | P99| 165ms| 135ms | -30ms | -18.184
| getChannelMembersForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 46ms| 45ms | -1ms | -2.159
| getChannelStats | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 84ms| 83ms | -1ms | -1.190
| getChannelUnread | Avg| 7ms| 4ms | -3ms | -45.617
| | P99| 81ms| 23ms | -58ms | -72.049
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getChannelsForUser | Avg| 9ms| 6ms | -3ms | -32.189
| | P99| 280ms| 45ms | -235ms | -83.924
| getClientConfig | Avg| 9ms| 8ms | -1ms | -11.077
| | P99| 125ms| 99ms | -26ms | -20.722
| getFilePreview | Avg| 47ms| 47ms | 0s | 0.000
| | P99| 227ms| 225ms | -2ms | -0.883
| getFileThumbnail | Avg| 36ms| 37ms | 1ms | 2.747
| | P99| 159ms| 165ms | 6ms | 3.784
| getPostThread | Avg| 14ms| 13ms | -1ms | -7.312
| | P99| 150ms| 126ms | -24ms | -15.965
| getPostsForChannel | Avg| 34ms| 32ms | -2ms | -5.937
| | P99| 278ms| 248ms | -30ms | -10.788
| getPostsForChannelAroundLastUnread | Avg| 29ms| 28ms | -1ms | -3.456
| | P99| 243ms| 242ms | -1ms | -0.411
| getPreferences | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 60ms| 55ms | -5ms | -8.295
| getProfileImage | Avg| 105ms| 105ms | 0s | 0.000
| | P99| 488ms| 490ms | 2ms | 0.410
| getPublicChannelsForTeam | Avg| 20ms| 21ms | 1ms | 4.952
| | P99| 48ms| 81ms | 33ms | 69.026
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 30ms| 23ms | -7ms | -23.119
| getTeamMembersForUser | Avg| 6ms| 5ms | -1ms | -17.421
| | P99| 75ms| 68ms | -7ms | -9.277
| getTeamsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 47ms| 46ms | -1ms | -2.135
| getTeamsUnreadForUser | Avg| 8ms| 7ms | -1ms | -12.741
| | P99| 87ms| 83ms | -4ms | -4.612
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 49ms| 47ms | -2ms | -4.107
| getUser | Avg| 7ms| 6ms | -1ms | -15.005
| | P99| 94ms| 95ms | 1ms | 1.069
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 0s | -1ms | -193.020
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 8ms | -1ms | -11.413
| | P99| 95ms| 93ms | -2ms | -2.095
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByNames | Avg| 4ms| 3ms | -1ms | -28.042
| | P99| 40ms| 36ms | -4ms | -10.037
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 85ms| 82ms | -3ms | -3.529
| | P99| 635ms| 500ms | -135ms | -21.255
| logout | Avg| 66ms| 60ms | -6ms | -9.073
| | P99| 237ms| 240ms | 3ms | 1.264
| patchPost | Avg| 40ms| 381ms | 341ms | 859.243
| | P99| 247ms| 249ms | 2ms | 0.811
| removeUserCustomStatus | Avg| 208ms| 214ms | 6ms | 2.878
| | P99| 492ms| 670ms | 178ms | 36.184
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 23ms| 22ms | -1ms | -4.324
| | P99| 208ms| 195ms | -13ms | -6.249
| searchAllChannels | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 166ms| 164ms | -2ms | -1.207
| searchGroupChannels | Avg| 13ms| 5ms | -8ms | -60.802
| | P99| 55ms| 48ms | -7ms | -12.713
| searchPostsInTeam | Avg| 190ms| 173ms | -17ms | -8.948
| | P99| 2.379s| 2.353s | -26ms | -1.093
| searchUsers | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| setPostReminder | Avg| 27ms| 15ms | -12ms | -45.233
| | P99| 97ms| 25ms | -72ms | -74.227
| unfollowThreadByUser | Avg| 11ms| 12ms | 1ms | 9.173
| | P99| 25ms| 38ms | 13ms | 52.476
| updateCategoriesForTeamForUser | Avg| 104ms| 59ms | -45ms | -43.128
| | P99| 243ms| 217ms | -26ms | -10.688
| updatePreferences | Avg| 7ms| 6ms | -1ms | -15.099
| | P99| 48ms| 45ms | -3ms | -6.200
| updateReadStateAllThreadsByUser | Avg| 3ms| 4ms | 1ms | 39.647
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 41ms| 40ms | -1ms | -2.418
| | P99| 247ms| 229ms | -18ms | -7.279
| updateUserCustomStatus | Avg| 208ms| 209ms | 1ms | 0.481
| | P99| 492ms| 492ms | 0s | 0.000
| uploadFileStream | Avg| 465ms| 480ms | 15ms | 3.227
| | P99| 1.596s| 1.973s | 377ms | 23.623
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 138ms| 107ms | -31ms | -22.545
