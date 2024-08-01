### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 1ms | 595ms | 594ms | 46462.55
| UserStore.GetUnreadCount | avg | 3ms | 6ms | 3ms | 105.82
| ChannelStore.AutocompleteInTeamForSearch | avg | 119ms | 186ms | 67ms | 56.20
| StatusStore.SaveOrUpdate | avg | 18ms | 22ms | 4ms | 21.86
| ChannelStore.GetMemberCount | avg | 125ms | 142ms | 17ms | 13.60
| UserStore.GetAllProfilesInChannel | avg | 427ms | 458ms | 31ms | 7.26
| PostStore.SearchPostsForUser | avg | 50ms | 53ms | 3ms | 5.97
| UserStore.AutocompleteUsersInChannel | avg | 195ms | 205ms | 10ms | 5.13
| UserStore.AnalyticsActiveCount | avg | 208ms | 215ms | 7ms | 3.36
| UserStore.Search | avg | 90ms | 92ms | 2ms | 2.22
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 276ms | 279ms | 3ms | 1.09
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 2.47s | 2.465s | 49729.22
| ChannelStore.AutocompleteInTeamForSearch | p99 | 499ms | 2.206s | 1.707s | 342.21
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 38ms | 28ms | 285.54
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 19ms | 14ms | 282.82
| UserStore.GetUnreadCount | p99 | 24ms | 85ms | 61ms | 255.89
| UserStore.GetByUsername | p99 | 7ms | 26ms | 19ms | 255.07
| UserStore.Get | p99 | 6ms | 18ms | 12ms | 218.16
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 28ms | 19ms | 200.45
| ReactionStore.GetForPost | p99 | 8ms | 24ms | 16ms | 195.51
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| ChannelStore.GetPublicChannelsForTeam | p99 | 24ms | 57ms | 33ms | 139.06
| ChannelStore.GetPinnedPostCount | p99 | 11ms | 25ms | 14ms | 125.67
| LinkMetadataStore.Get | p99 | 5ms | 10ms | 5ms | 100.09
| JobStore.Save | p99 | 10ms | 18ms | 8ms | 82.31
| JobStore.GetCountByStatusAndType | p99 | 21ms | 38ms | 17ms | 82.03
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 18ms | 8ms | 81.63
| ChannelStore.GetMemberCount | p99 | 494ms | 872ms | 378ms | 76.59
| UserStore.Count | p99 | 248ms | 410ms | 162ms | 65.33
| TeamStore.Get | p99 | 11ms | 18ms | 7ms | 60.95
| PostStore.GetSingle | p99 | 5ms | 8ms | 3ms | 60.13
| UserStore.AutocompleteUsersInChannel | p99 | 493ms | 750ms | 257ms | 52.09
| ChannelStore.GetAllChannelMembersForUser | p99 | 42ms | 62ms | 20ms | 47.65
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 98ms | 137ms | 39ms | 39.92
| ChannelStore.Save | p99 | 48ms | 65ms | 17ms | 35.67
| FileInfoStore.GetForPost | p99 | 6ms | 8ms | 2ms | 33.99
| UserStore.Update | p99 | 18ms | 23ms | 5ms | 28.36
| FileInfoStore.Save | p99 | 12ms | 15ms | 3ms | 24.52
| JobStore.GetAllByStatus | p99 | 19ms | 23ms | 4ms | 21.39
| ProductNoticesStore.View | p99 | 128ms | 150ms | 22ms | 17.13
| UserStore.GetAllProfilesInChannel | p99 | 2.002s | 2.305s | 303ms | 15.13
| UserStore.Search | p99 | 298ms | 338ms | 40ms | 13.43
| PostStore.GetPostIdAfterTime | p99 | 17ms | 19ms | 2ms | 11.60
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 160ms | 178ms | 18ms | 11.22
| ChannelStore.GetMember | p99 | 20ms | 22ms | 2ms | 9.96
| PostStore.Update | p99 | 41ms | 45ms | 4ms | 9.68
| UserStore.UpdateLastLogin | p99 | 21ms | 23ms | 2ms | 9.52
| UserStore.IsEmpty | p99 | 41ms | 44ms | 3ms | 7.34
| ChannelStore.Get | p99 | 41ms | 44ms | 3ms | 7.32
| PostStore.GetPostsSince | p99 | 68ms | 72ms | 4ms | 5.90
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 44ms | 46ms | 2ms | 4.54
| UserStore.GetAllProfiles | p99 | 49ms | 51ms | 2ms | 4.11
| StatusStore.SaveOrUpdate | p99 | 232ms | 241ms | 9ms | 3.87
| PostStore.GetPosts | p99 | 59ms | 61ms | 2ms | 3.39
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | avg | 5ms | 1ms | -4ms | -74.11
| CommandWebhookStore.Cleanup | avg | 6ms | 2ms | -4ms | -72.62
| PluginStore.List | avg | 4ms | 1ms | -3ms | -68.03
| ThreadStore.MarkAllAsReadByTeam | avg | 6ms | 4ms | -2ms | -33.81
| ChannelStore.GetChannelsByUser | avg | 7ms | 5ms | -2ms | -30.42
| ChannelStore.GetSidebarCategory | avg | 7ms | 5ms | -2ms | -29.98
| ChannelStore.CreateSidebarCategory | avg | 26ms | 22ms | -4ms | -15.31
| ChannelStore.UpdateSidebarCategories | avg | 49ms | 42ms | -7ms | -14.35
| UserStore.Count | avg | 102ms | 97ms | -5ms | -4.89
| ChannelStore.Autocomplete | avg | 1.51s | 1.485s | -25ms | -1.66
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.List | p99 | 196ms | 20ms | -176ms | -89.78
| JobStore.Get | p99 | 30ms | 5ms | -25ms | -84.01
| PostAcknowledgementStore.GetForPost | p99 | 46ms | 7ms | -39ms | -83.87
| ChannelStore.SearchGroupChannels | p99 | 41ms | 8ms | -33ms | -80.44
| TeamStore.AnalyticsTeamCount | p99 | 24ms | 5ms | -19ms | -78.84
| ChannelStore.GetSidebarCategory | p99 | 85ms | 20ms | -65ms | -76.47
| PostPriorityStore.GetForPost | p99 | 39ms | 9ms | -30ms | -75.95
| BotStore.Get | p99 | 22ms | 5ms | -17ms | -75.72
| ThreadStore.Get | p99 | 17ms | 5ms | -12ms | -69.17
| SessionStore.Remove | p99 | 10ms | 5ms | -5ms | -51.55
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 25ms | -25ms | -50.51
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -50.50
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 5ms | -5ms | -50.25
| JobStore.UpdateStatus | p99 | 39ms | 21ms | -18ms | -46.75
| ChannelStore.GetFileCount | p99 | 47ms | 25ms | -22ms | -46.56
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.51
| FileInfoStore.Get | p99 | 9ms | 5ms | -4ms | -44.68
| ChannelStore.GetChannelsByUser | p99 | 93ms | 53ms | -40ms | -43.01
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 57ms | 36ms | -21ms | -36.68
| ChannelStore.CreateInitialSidebarCategories | p99 | 152ms | 98ms | -54ms | -35.46
| JobStore.UpdateOptimistically | p99 | 20ms | 13ms | -7ms | -34.91
| LinkMetadataStore.Save | p99 | 22ms | 15ms | -7ms | -31.89
| ThreadStore.GetThreadsForUser | p99 | 33ms | 24ms | -9ms | -27.60
| ThreadStore.GetThreadUnreadReplyCount | p99 | 7ms | 5ms | -2ms | -27.12
| PostStore.Get | p99 | 34ms | 25ms | -9ms | -26.50
| PostStore.GetEtag | p99 | 68ms | 52ms | -16ms | -23.37
| UserStore.GetProfilesByUsernames | p99 | 22ms | 17ms | -5ms | -23.05
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 9ms | 7ms | -2ms | -21.51
| ThreadStore.GetTotalUnreadMentions | p99 | 56ms | 45ms | -11ms | -19.79
| PostStore.GetPostsBefore | p99 | 32ms | 26ms | -6ms | -18.57
| TeamStore.GetTeamsForUser | p99 | 56ms | 47ms | -9ms | -16.04
| GroupStore.GetByName | p99 | 76ms | 64ms | -12ms | -15.82
| UserTermsOfServiceStore.GetByUser | p99 | 72ms | 61ms | -11ms | -15.31
| ChannelStore.GetByName | p99 | 66ms | 56ms | -10ms | -15.19
| UserStore.GetForLogin | p99 | 87ms | 74ms | -13ms | -14.86
| ThreadStore.GetThreadFollowers | p99 | 27ms | 23ms | -4ms | -14.68
| StatusStore.GetByIds | p99 | 48ms | 41ms | -7ms | -14.66
| PostPriorityStore.GetForPosts | p99 | 28ms | 24ms | -4ms | -14.42
| SessionStore.Get | p99 | 85ms | 73ms | -12ms | -14.20
| PreferenceStore.Get | p99 | 23ms | 20ms | -3ms | -12.82
| PostPersistentNotificationStore.GetSingle | p99 | 24ms | 21ms | -3ms | -12.74
| ThreadStore.GetTotalThreads | p99 | 48ms | 42ms | -6ms | -12.61
| SessionStore.Save | p99 | 80ms | 70ms | -10ms | -12.47
| ThreadStore.GetMembershipForUser | p99 | 25ms | 22ms | -3ms | -12.05
| TeamStore.GetAllPage | p99 | 61ms | 54ms | -7ms | -11.47
| ChannelStore.GetChannels | p99 | 44ms | 39ms | -5ms | -11.36
| ChannelStore.GetMemberForPost | p99 | 18ms | 16ms | -2ms | -11.09
| PreferenceStore.GetAll | p99 | 93ms | 83ms | -10ms | -10.79
| ThreadStore.GetThreadForUser | p99 | 28ms | 25ms | -3ms | -10.65
| StatusStore.Get | p99 | 51ms | 46ms | -5ms | -9.84
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 21ms | 19ms | -2ms | -9.31
| ThreadStore.GetTotalUnreadThreads | p99 | 47ms | 43ms | -4ms | -8.49
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 48ms | 44ms | -4ms | -8.27
| PostAcknowledgementStore.GetForPosts | p99 | 24ms | 22ms | -2ms | -8.24
| ChannelStore.GetGuestCount | p99 | 83ms | 77ms | -6ms | -7.27
| ChannelStore.UpdateSidebarCategories | p99 | 237ms | 220ms | -17ms | -7.17
| TeamStore.GetTeamsByUserId | p99 | 60ms | 56ms | -4ms | -6.65
| ChannelStore.GetMembersForUser | p99 | 38ms | 36ms | -2ms | -5.27
| PreferenceStore.Save | p99 | 47ms | 45ms | -2ms | -4.27
| UserStore.Save | p99 | 162ms | 158ms | -4ms | -2.46
| ChannelStore.SaveMember | p99 | 249ms | 245ms | -4ms | -1.61
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 119ms | 186ms | 67ms | 56.17
| logout | avg | 35ms | 43ms | 8ms | 22.76
| createPost | avg | 351ms | 413ms | 62ms | 17.67
| getFilteredUsersStats | avg | 54ms | 63ms | 9ms | 16.58
| autocompleteUsers | avg | 158ms | 168ms | 10ms | 6.31
| removeUserCustomStatus | avg | 140ms | 148ms | 8ms | 5.70
| searchPostsInTeam | avg | 54ms | 57ms | 3ms | 5.57
| createChannel | avg | 264ms | 278ms | 14ms | 5.31
| addTeamMember | avg | 1.218s | 1.268s | 50ms | 4.11
| addChannelMember | avg | 204ms | 207ms | 3ms | 1.47
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 499ms | 2.206s | 1.707s | 342.21
| getPublicChannelsForTeam | p99 | 25ms | 57ms | 32ms | 128.95
| logout | p99 | 50ms | 98ms | 48ms | 96.48
| autocompleteUsers | p99 | 478ms | 606ms | 128ms | 26.76
| searchPostsInTeam | p99 | 315ms | 391ms | 76ms | 24.13
| getChannelStats | p99 | 283ms | 348ms | 65ms | 22.98
| getCategoriesForTeamForUser | p99 | 162ms | 179ms | 17ms | 10.51
| searchUsers | p99 | 322ms | 350ms | 28ms | 8.70
| createPost | p99 | 2.133s | 2.292s | 159ms | 7.45
| addTeamMember | p99 | 4.457s | 4.738s | 281ms | 6.31
| addChannelMember | p99 | 477ms | 500ms | 23ms | 4.82
| getPostsForChannelAroundLastUnread | p99 | 238ms | 241ms | 3ms | 1.26
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 50ms | 32ms | -18ms | -36.20
| updateReadStateAllThreadsByUser | avg | 6ms | 4ms | -2ms | -33.25
| createCategoryForTeamForUser | avg | 32ms | 23ms | -9ms | -28.41
| getChannel | avg | 8ms | 6ms | -2ms | -26.47
| updateCategoriesForTeamForUser | avg | 67ms | 53ms | -14ms | -20.84
| getProfileImage | avg | 87ms | 81ms | -6ms | -6.89
| uploadFileStream | avg | 409ms | 387ms | -22ms | -5.38
| getAnalytics | avg | 228ms | 217ms | -11ms | -4.83
| createDirectChannel | avg | 244ms | 235ms | -9ms | -3.69
| searchAllChannels | avg | 1.511s | 1.485s | -26ms | -1.72
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| deleteDraft | p99 | 5ms | 0s | -5ms | -101.01
| searchGroupChannels | p99 | 41ms | 8ms | -33ms | -80.44
| getChannel | p99 | 166ms | 49ms | -117ms | -70.48
| updateCategoriesForTeamForUser | p99 | 458ms | 220ms | -238ms | -52.02
| createCategoryForTeamForUser | p99 | 50ms | 25ms | -25ms | -50.51
| updateReadStateAllThreadsByUser | p99 | 10ms | 5ms | -5ms | -50.25
| patchPost | p99 | 493ms | 248ms | -245ms | -49.74
| getChannelsForUser | p99 | 146ms | 82ms | -64ms | -43.69
| unfollowThreadByUser | p99 | 40ms | 25ms | -15ms | -37.74
| createGroupChannel | p99 | 790ms | 497ms | -293ms | -37.09
| getChannelMember | p99 | 175ms | 125ms | -50ms | -28.52
| getUsersByNames | p99 | 22ms | 17ms | -5ms | -22.71
| getTeamMembersForUser | p99 | 71ms | 56ms | -15ms | -21.22
| viewChannel | p99 | 69ms | 56ms | -13ms | -18.78
| getChannelsForTeamForUser | p99 | 62ms | 51ms | -11ms | -17.84
| getThreadsForUser | p99 | 42ms | 36ms | -6ms | -14.45
| getFilePreview | p99 | 191ms | 169ms | -22ms | -11.54
| getClientConfig | p99 | 53ms | 47ms | -6ms | -11.29
| updateReadStateThreadByUser | p99 | 81ms | 72ms | -9ms | -11.05
| getUser | p99 | 85ms | 76ms | -9ms | -10.60
| getPreferences | p99 | 93ms | 84ms | -9ms | -9.70
| saveReaction | p99 | 85ms | 79ms | -6ms | -7.09
| getTeamsForUser | p99 | 61ms | 57ms | -4ms | -6.54
| getProfileImage | p99 | 422ms | 399ms | -23ms | -5.44
| getChannelMembersForTeamForUser | p99 | 43ms | 41ms | -2ms | -4.65
| login | p99 | 450ms | 432ms | -18ms | -4.00
| getFileThumbnail | p99 | 93ms | 90ms | -3ms | -3.21
| getAllTeams | p99 | 69ms | 67ms | -2ms | -2.88
| getTeamsUnreadForUser | p99 | 87ms | 85ms | -2ms | -2.31
| getPostsForChannel | p99 | 183ms | 180ms | -3ms | -1.64
| createUser | p99 | 457ms | 450ms | -7ms | -1.53
| uploadFileStream | p99 | 997ms | 987ms | -10ms | -1.00
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -54.064
| |  P99| 22ms| 5ms | -17ms | -75.724
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 276ms| 279ms | 3ms | 1.087
| |  P99| 497ms| 497ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.597
| ChannelStore.AnalyticsTypeCount |  Avg| 3ms| 4ms | 1ms | 28.983
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 1.51s| 1.485s | -25ms | -1.655
| |  P99| 4.937s| 4.954s | 17ms | 0.344
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 119ms| 186ms | 67ms | 56.199
| |  P99| 499ms| 2.206s | 1.707s | 342.213
| ChannelStore.CreateDirectChannel |  Avg| 19ms| 20ms | 1ms | 5.202
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 152ms| 98ms | -54ms | -35.462
| ChannelStore.CreateSidebarCategory |  Avg| 26ms| 22ms | -4ms | -15.310
| |  P99| 50ms| 25ms | -25ms | -50.505
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 41ms| 44ms | 3ms | 7.315
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 57ms| 36ms | -21ms | -36.681
| ChannelStore.GetAllChannelMembersForUser |  Avg| 8ms| 9ms | 1ms | 13.329
| |  P99| 42ms| 62ms | 20ms | 47.654
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 16ms | 1ms | 6.572
| |  P99| 98ms| 137ms | 39ms | 39.915
| ChannelStore.GetByName |  Avg| 4ms| 5ms | 1ms | 22.546
| |  P99| 66ms| 56ms | -10ms | -15.192
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 44ms| 39ms | -5ms | -11.356
| ChannelStore.GetChannelsByUser |  Avg| 7ms| 5ms | -2ms | -30.419
| |  P99| 93ms| 53ms | -40ms | -43.011
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.313
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 47ms| 25ms | -22ms | -46.561
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 83ms| 77ms | -6ms | -7.270
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.961
| ChannelStore.GetMemberCount |  Avg| 125ms| 142ms | 17ms | 13.596
| |  P99| 494ms| 872ms | 378ms | 76.587
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 16ms | -2ms | -11.087
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 3ms | 1ms | 42.666
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.271
| ChannelStore.GetMembersForUserWithPagination |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 25ms | 14ms | 125.673
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 10ms | 1ms | 10.585
| |  P99| 24ms| 57ms | 33ms | 139.055
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 9ms| 10ms | 1ms | 11.157
| |  P99| 160ms| 178ms | 18ms | 11.225
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 5ms | -2ms | -29.978
| |  P99| 85ms| 20ms | -65ms | -76.468
| ChannelStore.GetTeamChannels |  Avg| 35ms| 34ms | -1ms | -2.827
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| ChannelStore.Save |  Avg| 13ms| 14ms | 1ms | 7.520
| |  P99| 48ms| 65ms | 17ms | 35.674
| ChannelStore.SaveMember |  Avg| 36ms| 37ms | 1ms | 2.803
| |  P99| 249ms| 245ms | -4ms | -1.607
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 1ms | -1ms | -44.517
| |  P99| 41ms| 8ms | -33ms | -80.445
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 49ms| 42ms | -7ms | -14.354
| |  P99| 237ms| 220ms | -17ms | -7.165
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 28ms | 19ms | 200.448
| CommandWebhookStore.Cleanup |  Avg| 6ms| 2ms | -4ms | -72.622
| |  P99| 10ms| 5ms | -5ms | -50.505
| ComplianceStore.MessageExport |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 0s | -1ms | -154.839
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.GetDraftsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.178
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 1ms| 0s | -1ms | -163.778
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 6ms| 7ms | 1ms | 15.442
| |  P99| 19ms| 19ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.676
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 33.992
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.522
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.270
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 3ms | 1ms | 42.373
| |  P99| 44ms| 46ms | 2ms | 4.536
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 76ms| 64ms | -12ms | -15.818
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.650
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 30ms| 5ms | -25ms | -84.008
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 23ms | 4ms | 21.390
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 87.082
| |  P99| 21ms| 38ms | 17ms | 82.027
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 81.633
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -22.040
| |  P99| 10ms| 18ms | 8ms | 82.310
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 13ms | -7ms | -34.913
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 21ms | -18ms | -46.753
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 5ms | 1ms | 23.186
| |  P99| 10ms| 38ms | 28ms | 285.537
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.092
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 15ms | -7ms | -31.890
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 4ms| 1ms | -3ms | -68.027
| |  P99| 196ms| 20ms | -176ms | -89.784
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.070
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -41.647
| |  P99| 46ms| 7ms | -39ms | -83.873
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.244
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.512
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.744
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -46.448
| |  P99| 39ms| 9ms | -30ms | -75.953
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.423
| PostStore.AnalyticsPostCount |  Avg| 1ms| 595ms | 594ms | 46462.550
| |  P99| 5ms| 2.47s | 2.465s | 49729.219
| PostStore.Delete |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 25ms | -9ms | -26.495
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 68ms| 52ms | -16ms | -23.365
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.596
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.514
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 5ms| 6ms | 1ms | 18.361
| |  P99| 59ms| 61ms | 2ms | 3.387
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 26ms | -6ms | -18.566
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 68ms| 72ms | 4ms | 5.898
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.128
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 50ms| 53ms | 3ms | 5.970
| |  P99| 247ms| 248ms | 1ms | 0.405
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 13.659
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 17ms| 18ms | 1ms | 5.803
| |  P99| 41ms| 45ms | 4ms | 9.678
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 1ms | -1ms | -66.099
| |  P99| 23ms| 20ms | -3ms | -12.823
| PreferenceStore.GetAll |  Avg| 6ms| 5ms | -1ms | -18.161
| |  P99| 93ms| 83ms | -10ms | -10.793
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.267
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 3ms | 1ms | 44.032
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 128ms| 150ms | 22ms | 17.131
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 24ms | 16ms | 195.515
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -97.927
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 2ms | 1ms | 79.564
| |  P99| 5ms| 19ms | 14ms | 282.824
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 7ms| 6ms | -1ms | -15.318
| |  P99| 85ms| 73ms | -12ms | -14.199
| SessionStore.GetLRUSessions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 83ms| 82ms | -1ms | -1.201
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.506
| SessionStore.Remove |  Avg| 5ms| 4ms | -1ms | -21.702
| |  P99| 10ms| 5ms | -5ms | -51.546
| SessionStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 70ms | -10ms | -12.467
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 51ms| 46ms | -5ms | -9.840
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 48ms| 41ms | -7ms | -14.658
| StatusStore.SaveOrUpdate |  Avg| 18ms| 22ms | 4ms | 21.860
| |  P99| 232ms| 241ms | 9ms | 3.875
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 8ms | 1ms | 13.496
| |  P99| 22ms| 22ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.461
| TeamStore.AnalyticsTeamCount |  Avg| 5ms| 1ms | -4ms | -74.111
| |  P99| 24ms| 5ms | -19ms | -78.838
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 18ms | 7ms | 60.955
| TeamStore.GetActiveMemberCount |  Avg| 153ms| 152ms | -1ms | -0.654
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 61ms| 54ms | -7ms | -11.470
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 60ms| 56ms | -4ms | -6.648
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 56ms| 47ms | -9ms | -16.040
| TeamStore.GetTotalMemberCount |  Avg| 115ms| 114ms | -1ms | -0.872
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 99ms| 99ms | 0s | 0.000
| |  P99| 246ms| 246ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -69.166
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 25ms| 22ms | -3ms | -12.051
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 4ms | 1ms | 29.819
| |  P99| 49ms| 50ms | 1ms | 2.020
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 27ms| 23ms | -4ms | -14.678
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.655
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.125
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 33ms| 24ms | -9ms | -27.598
| ThreadStore.GetTotalThreads |  Avg| 3ms| 2ms | -1ms | -39.977
| |  P99| 48ms| 42ms | -6ms | -12.605
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 56ms| 45ms | -11ms | -19.786
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 47ms| 43ms | -4ms | -8.487
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 48ms| 44ms | -4ms | -8.273
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.437
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.309
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 4ms | -2ms | -33.809
| |  P99| 10ms| 5ms | -5ms | -50.251
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.303
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 208ms| 215ms | 7ms | 3.357
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 195ms| 205ms | 10ms | 5.131
| |  P99| 493ms| 750ms | 257ms | 52.091
| UserStore.Count |  Avg| 102ms| 97ms | -5ms | -4.891
| |  P99| 248ms| 410ms | 162ms | 65.328
| UserStore.Get |  Avg| 1ms| 2ms | 1ms | 82.253
| |  P99| 6ms| 18ms | 12ms | 218.161
| UserStore.GetAllProfiles |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 51ms | 2ms | 4.107
| UserStore.GetAllProfilesInChannel |  Avg| 427ms| 458ms | 31ms | 7.255
| |  P99| 2.002s| 2.305s | 303ms | 15.132
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 26ms | 19ms | 255.071
| UserStore.GetForLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 87ms| 74ms | -13ms | -14.864
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 17ms | -5ms | -23.055
| UserStore.GetProfilesInChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 6ms | 3ms | 105.824
| |  P99| 24ms| 85ms | 61ms | 255.887
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 41ms| 44ms | 3ms | 7.345
| UserStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 162ms| 158ms | -4ms | -2.462
| UserStore.Search |  Avg| 90ms| 92ms | 2ms | 2.223
| |  P99| 298ms| 338ms | 40ms | 13.431
| UserStore.Update |  Avg| 6ms| 7ms | 1ms | 15.446
| |  P99| 18ms| 23ms | 5ms | 28.364
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.520
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 72ms| 61ms | -11ms | -15.305
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 31ms | 1ms | 3.381
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 204ms| 207ms | 3ms | 1.471
| | P99| 477ms| 500ms | 23ms | 4.824
| addTeamMember | Avg| 1.218s| 1.268s | 50ms | 4.105
| | P99| 4.457s| 4.738s | 281ms | 6.305
| autocompleteChannelsForTeamForSearch | Avg| 119ms| 186ms | 67ms | 56.166
| | P99| 499ms| 2.206s | 1.707s | 342.213
| autocompleteEmojis | Avg| 1ms| 0s | -1ms | -150.299
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 158ms| 168ms | 10ms | 6.313
| | P99| 478ms| 606ms | 128ms | 26.763
| createCategoryForTeamForUser | Avg| 32ms| 23ms | -9ms | -28.411
| | P99| 50ms| 25ms | -25ms | -50.505
| createChannel | Avg| 264ms| 278ms | 14ms | 5.312
| | P99| 498ms| 497ms | -1ms | -0.201
| createDirectChannel | Avg| 244ms| 235ms | -9ms | -3.686
| | P99| 494ms| 492ms | -2ms | -0.405
| createGroupChannel | Avg| 346ms| 344ms | -2ms | -0.579
| | P99| 790ms| 497ms | -293ms | -37.090
| createPost | Avg| 351ms| 413ms | 62ms | 17.674
| | P99| 2.133s| 2.292s | 159ms | 7.453
| createUser | Avg| 137ms| 137ms | 0s | 0.000
| | P99| 457ms| 450ms | -7ms | -1.532
| deleteDraft | Avg| 1ms| 0s | -1ms | -143.816
| | P99| 5ms| 0s | -5ms | -101.010
| deletePost | Avg| 18ms| 19ms | 1ms | 5.545
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 10ms | 1ms | 10.567
| | P99| 24ms| 24ms | 0s | 0.000
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 69ms| 67ms | -2ms | -2.879
| getAnalytics | Avg| 228ms| 217ms | -11ms | -4.826
| | P99| 494ms| 493ms | -1ms | -0.202
| getCategoriesForTeamForUser | Avg| 9ms| 10ms | 1ms | 10.930
| | P99| 162ms| 179ms | 17ms | 10.506
| getChannel | Avg| 8ms| 6ms | -2ms | -26.467
| | P99| 166ms| 49ms | -117ms | -70.482
| getChannelMember | Avg| 10ms| 9ms | -1ms | -9.715
| | P99| 175ms| 125ms | -50ms | -28.516
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.652
| getChannelMembersForUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 13ms| 14ms | 1ms | 7.998
| | P99| 283ms| 348ms | 65ms | 22.977
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 62ms| 51ms | -11ms | -17.835
| getChannelsForUser | Avg| 7ms| 6ms | -1ms | -13.877
| | P99| 146ms| 82ms | -64ms | -43.690
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 53ms| 47ms | -6ms | -11.294
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 1ms| 2ms | 1ms | 106.670
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 42ms| 41ms | -1ms | -2.372
| | P99| 191ms| 169ms | -22ms | -11.540
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.158
| | P99| 93ms| 90ms | -3ms | -3.213
| getFilteredUsersStats | Avg| 54ms| 63ms | 9ms | 16.576
| | P99| 246ms| 246ms | 0s | 0.000
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.531
| getPostsForChannel | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 183ms| 180ms | -3ms | -1.636
| getPostsForChannelAroundLastUnread | Avg| 23ms| 24ms | 1ms | 4.422
| | P99| 238ms| 241ms | 3ms | 1.263
| getPreferences | Avg| 6ms| 5ms | -1ms | -17.757
| | P99| 93ms| 84ms | -9ms | -9.703
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 0s | -1ms | -87.849
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 87ms| 81ms | -6ms | -6.892
| | P99| 422ms| 399ms | -23ms | -5.445
| getPublicChannelsForTeam | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 57ms | 32ms | 128.950
| getRolesByNames | Avg| 0s| 1ms | 1ms | 360.808
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 71ms| 56ms | -15ms | -21.218
| getTeamStats | Avg| 155ms| 155ms | 0s | 0.000
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 61ms| 57ms | -4ms | -6.539
| getTeamsUnreadForUser | Avg| 5ms| 6ms | 1ms | 19.005
| | P99| 87ms| 85ms | -2ms | -2.306
| getThreadsForUser | Avg| 3ms| 2ms | -1ms | -39.494
| | P99| 42ms| 36ms | -6ms | -14.449
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 85ms| 76ms | -9ms | -10.596
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 17ms | -5ms | -22.713
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 80ms| 79ms | -1ms | -1.252
| | P99| 450ms| 432ms | -18ms | -3.998
| logout | Avg| 35ms| 43ms | 8ms | 22.755
| | P99| 50ms| 98ms | 48ms | 96.482
| patchPost | Avg| 50ms| 32ms | -18ms | -36.201
| | P99| 493ms| 248ms | -245ms | -49.743
| removeUserCustomStatus | Avg| 140ms| 148ms | 8ms | 5.696
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 85ms| 79ms | -6ms | -7.087
| searchAllChannels | Avg| 1.511s| 1.485s | -26ms | -1.721
| | P99| 4.937s| 4.954s | 17ms | 0.344
| searchGroupChannels | Avg| 2ms| 1ms | -1ms | -43.223
| | P99| 41ms| 8ms | -33ms | -80.445
| searchPostsInTeam | Avg| 54ms| 57ms | 3ms | 5.573
| | P99| 315ms| 391ms | 76ms | 24.127
| searchUsers | Avg| 92ms| 93ms | 1ms | 1.088
| | P99| 322ms| 350ms | 28ms | 8.704
| setPostReminder | Avg| 11ms| 12ms | 1ms | 8.753
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 40ms| 25ms | -15ms | -37.737
| updateCategoriesForTeamForUser | Avg| 67ms| 53ms | -14ms | -20.843
| | P99| 458ms| 220ms | -238ms | -52.021
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 6ms| 4ms | -2ms | -33.247
| | P99| 10ms| 5ms | -5ms | -50.251
| updateReadStateThreadByUser | Avg| 21ms| 20ms | -1ms | -4.818
| | P99| 81ms| 72ms | -9ms | -11.048
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 409ms| 387ms | -22ms | -5.382
| | P99| 997ms| 987ms | -10ms | -1.003
| upsertDraft | Avg| 3ms| 2ms | -1ms | -38.230
| | P99| 5ms| 5ms | 0s | 0.000
| viewChannel | Avg| 11ms| 10ms | -1ms | -9.481
| | P99| 69ms| 56ms | -13ms | -18.782
