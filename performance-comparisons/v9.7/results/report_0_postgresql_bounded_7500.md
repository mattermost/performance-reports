### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMembersForUser | avg | 1ms | 6ms | 5ms | 885.68
| JobStore.UpdateOptimistically | avg | 2ms | 4ms | 2ms | 87.20
| PostStore.GetPostReminders | avg | 3ms | 5ms | 2ms | 62.92
| ChannelStore.AutocompleteInTeamForSearch | avg | 85ms | 114ms | 29ms | 34.25
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 24ms | 30ms | 6ms | 24.94
| ChannelStore.Save | avg | 9ms | 11ms | 2ms | 23.22
| ChannelStore.UpdateSidebarCategories | avg | 54ms | 66ms | 12ms | 22.09
| StatusStore.SaveOrUpdate | avg | 64ms | 76ms | 12ms | 18.86
| ChannelStore.GetSidebarCategory | avg | 15ms | 17ms | 2ms | 13.08
| ChannelStore.GetTeamChannels | avg | 19ms | 21ms | 2ms | 10.29
| ChannelStore.SaveMember | avg | 32ms | 34ms | 2ms | 6.21
| ChannelStore.CreateInitialSidebarCategories | avg | 39ms | 41ms | 2ms | 5.08
| PostStore.SearchPostsForUser | avg | 167ms | 174ms | 7ms | 4.20
| UserStore.GetAllProfilesInChannel | avg | 258ms | 263ms | 5ms | 1.94
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.UpdateOptimistically | p99 | 5ms | 39ms | 34ms | 686.87
| PostStore.GetPostReminders | p99 | 5ms | 22ms | 17ms | 343.43
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 22ms | 17ms | 343.43
| BotStore.Get | p99 | 5ms | 22ms | 17ms | 343.43
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.UpdateStatus | p99 | 5ms | 19ms | 14ms | 282.83
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 97ms | 354ms | 257ms | 264.65
| ChannelStore.GetAllChannelMembersForUser | p99 | 10ms | 29ms | 19ms | 192.66
| ClusterDiscoveryStore.SetLastPingAt | p99 | 12ms | 30ms | 18ms | 154.51
| UserStore.GetMany | p99 | 9ms | 23ms | 14ms | 153.01
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 59ms | 34ms | 136.73
| PostStore.GetPostsAfter | p99 | 9ms | 20ms | 11ms | 127.91
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 19ms | 10ms | 116.28
| UserStore.GetByUsername | p99 | 22ms | 44ms | 22ms | 100.92
| UserStore.Get | p99 | 10ms | 19ms | 9ms | 89.25
| UserStore.AnalyticsActiveCount | p99 | 25ms | 47ms | 22ms | 88.45
| JobStore.UpdateStatusOptimistically | p99 | 5ms | 9ms | 4ms | 80.81
| TeamStore.GetMember | p99 | 5ms | 9ms | 4ms | 76.92
| JobStore.GetCountByStatusAndType | p99 | 38ms | 67ms | 29ms | 76.82
| PostStore.Update | p99 | 49ms | 86ms | 37ms | 75.00
| RoleStore.ChannelHigherScopedPermissions | p99 | 23ms | 39ms | 16ms | 68.30
| JobStore.GetAllByStatus | p99 | 28ms | 45ms | 17ms | 61.68
| ChannelStore.Save | p99 | 56ms | 82ms | 26ms | 46.43
| ThreadStore.MarkAsRead | p99 | 9ms | 13ms | 4ms | 42.69
| ThreadStore.Get | p99 | 5ms | 7ms | 2ms | 40.40
| JobStore.GetNewestJobByStatusesAndType | p99 | 18ms | 25ms | 7ms | 39.66
| StatusStore.GetByIds | p99 | 16ms | 22ms | 6ms | 37.28
| GroupStore.GetByName | p99 | 25ms | 34ms | 9ms | 35.35
| UserStore.UpdateFailedPasswordAttempts | p99 | 25ms | 33ms | 8ms | 32.38
| PostStore.Save | p99 | 48ms | 62ms | 14ms | 28.94
| TeamStore.GetAllPage | p99 | 24ms | 30ms | 6ms | 24.65
| ThreadStore.GetThreadForUser | p99 | 25ms | 31ms | 6ms | 24.09
| PostStore.GetEtag | p99 | 24ms | 29ms | 5ms | 20.56
| ChannelStore.GetMemberForPost | p99 | 20ms | 24ms | 4ms | 19.88
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 15ms | 18ms | 3ms | 19.38
| ChannelStore.GetMember | p99 | 24ms | 28ms | 4ms | 16.54
| ChannelStore.GetByName | p99 | 38ms | 44ms | 6ms | 15.72
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.28s | 3.792s | 512ms | 15.61
| PostPersistentNotificationStore.GetSingle | p99 | 14ms | 16ms | 2ms | 14.62
| SessionStore.Get | p99 | 50ms | 57ms | 7ms | 13.90
| TeamStore.SaveMember | p99 | 96ms | 109ms | 13ms | 13.58
| ChannelStore.SaveMember | p99 | 175ms | 198ms | 23ms | 13.12
| StatusStore.Get | p99 | 24ms | 27ms | 3ms | 12.61
| ChannelStore.GetGuestCount | p99 | 33ms | 37ms | 4ms | 12.26
| PostStore.GetPostIdBeforeTime | p99 | 16ms | 18ms | 2ms | 12.23
| PostStore.GetPosts | p99 | 25ms | 28ms | 3ms | 12.09
| AuditStore.Save | p99 | 25ms | 28ms | 3ms | 11.78
| ChannelStore.CreateInitialSidebarCategories | p99 | 179ms | 199ms | 20ms | 11.20
| PluginStore.Delete | p99 | 18ms | 20ms | 2ms | 10.85
| StatusStore.SaveOrUpdate | p99 | 812ms | 896ms | 84ms | 10.35
| UserStore.GetUnreadCount | p99 | 20ms | 22ms | 2ms | 10.15
| ChannelStore.GetFileCount | p99 | 20ms | 22ms | 2ms | 9.90
| SessionStore.Save | p99 | 41ms | 45ms | 4ms | 9.85
| PreferenceStore.Save | p99 | 73ms | 80ms | 7ms | 9.55
| SystemStore.GetByName | p99 | 22ms | 24ms | 2ms | 8.98
| FileInfoStore.Save | p99 | 23ms | 25ms | 2ms | 8.87
| ThreadStore.MaintainMembership | p99 | 24ms | 26ms | 2ms | 8.39
| TeamStore.GetTeamsForUser | p99 | 24ms | 26ms | 2ms | 8.25
| ChannelStore.GetPublicChannelsForTeam | p99 | 69ms | 73ms | 4ms | 5.76
| WebhookStore.GetOutgoingByTeam | p99 | 40ms | 42ms | 2ms | 4.94
| ChannelStore.SearchGroupChannels | p99 | 42ms | 44ms | 2ms | 4.76
| ProductNoticesStore.View | p99 | 224ms | 233ms | 9ms | 4.02
| UserStore.Save | p99 | 218ms | 221ms | 3ms | 1.38
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetByNameIncludeDeleted | avg | 2ms | 0s | -2ms | -119.70
| SessionStore.GetLRUSessions | avg | 3ms | 0s | -3ms | -111.96
| PostStore.AnalyticsPostCount | avg | 450ms | 0s | -450ms | -100.02
| ProductNoticesStore.ClearOldNotices | avg | 65ms | 0s | -65ms | -99.89
| TeamStore.GetByName | avg | 2ms | 0s | -2ms | -89.64
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -88.19
| TeamStore.AnalyticsTeamCount | avg | 6ms | 2ms | -4ms | -64.07
| PostStore.SetPostReminder | avg | 7ms | 4ms | -3ms | -42.10
| ChannelStore.AnalyticsTypeCount | avg | 13ms | 8ms | -5ms | -37.94
| ChannelStore.CreateDirectChannel | avg | 21ms | 19ms | -2ms | -9.69
| UserStore.GetProfilesInChannel | avg | 38ms | 35ms | -3ms | -7.87
| UserStore.AutocompleteUsersInChannel | avg | 49ms | 47ms | -2ms | -4.05
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.GetLRUSessions | p99 | 23ms | 0s | -23ms | -101.04
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.InvalidateChannelByName | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.InvalidateAllChannelMembersForUser | p99 | 5ms | 0s | -5ms | -101.00
| ProductNoticesStore.ClearOldNotices | p99 | 100ms | 0s | -100ms | -100.50
| TeamStore.GetByName | p99 | 25ms | 0s | -25ms | -100.20
| PostStore.AnalyticsPostCount | p99 | 498ms | 0s | -498ms | -100.10
| JobStore.Get | p99 | 21ms | 8ms | -13ms | -60.75
| TeamStore.AnalyticsTeamCount | p99 | 25ms | 10ms | -15ms | -60.73
| ChannelStore.AnalyticsTypeCount | p99 | 25ms | 10ms | -15ms | -60.31
| ChannelStore.GetChannelsByUser | p99 | 15ms | 6ms | -9ms | -59.02
| PostStore.SetPostReminder | p99 | 24ms | 10ms | -14ms | -58.27
| PostPersistentNotificationStore.Get | p99 | 21ms | 9ms | -12ms | -58.11
| PostStore.GetPostReminderMetadata | p99 | 21ms | 9ms | -12ms | -56.84
| ChannelStore.GetPinnedPostCount | p99 | 23ms | 10ms | -13ms | -56.69
| JobStore.Save | p99 | 18ms | 8ms | -10ms | -55.71
| UserStore.GetProfilesInChannel | p99 | 92ms | 50ms | -42ms | -45.65
| ReactionStore.GetForPost | p99 | 22ms | 12ms | -10ms | -44.62
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -42.78
| UserStore.Update | p99 | 69ms | 44ms | -25ms | -36.39
| EmojiStore.GetByName | p99 | 20ms | 15ms | -5ms | -24.48
| PostStore.GetSingle | p99 | 13ms | 10ms | -3ms | -23.81
| FileInfoStore.SetContent | p99 | 40ms | 31ms | -9ms | -22.33
| FileInfoStore.Get | p99 | 14ms | 11ms | -3ms | -22.17
| LinkMetadataStore.Get | p99 | 15ms | 12ms | -3ms | -20.69
| ChannelStore.CreateDirectChannel | p99 | 93ms | 75ms | -18ms | -19.39
| UserStore.AutocompleteUsersInChannel | p99 | 353ms | 298ms | -55ms | -15.57
| PluginStore.SetWithOptions | p99 | 35ms | 30ms | -5ms | -14.16
| ChannelStore.GetChannelUnread | p99 | 21ms | 19ms | -2ms | -9.62
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 85ms | 114ms | 29ms | 34.23
| createUser | avg | 101ms | 134ms | 33ms | 32.75
| updateCategoriesForTeamForUser | avg | 87ms | 102ms | 15ms | 17.15
| getLicenseSelfServeStatus | avg | 56ms | 64ms | 8ms | 14.31
| getProfileImage | avg | 79ms | 88ms | 9ms | 11.33
| getAnalytics | avg | 36ms | 40ms | 4ms | 11.24
| createDirectChannel | avg | 229ms | 239ms | 10ms | 4.38
| searchPostsInTeam | avg | 175ms | 182ms | 7ms | 4.00
| addTeamMember | avg | 848ms | 880ms | 32ms | 3.78
| uploadFileStream | avg | 376ms | 390ms | 14ms | 3.72
| createPost | avg | 312ms | 318ms | 6ms | 1.92
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | p99 | 5ms | 10ms | 5ms | 100.95
| root | p99 | 5ms | 9ms | 4ms | 80.81
| createUser | p99 | 316ms | 477ms | 161ms | 50.98
| updateReadStateThreadByUser | p99 | 131ms | 182ms | 51ms | 39.01
| getAllTeams | p99 | 30ms | 37ms | 7ms | 23.38
| getTeamMember | p99 | 19ms | 23ms | 4ms | 21.44
| autocompleteChannelsForTeamForSearch | p99 | 3.28s | 3.792s | 512ms | 15.61
| getClientConfig | p99 | 64ms | 73ms | 9ms | 14.11
| getTeamMembersForUser | p99 | 36ms | 41ms | 5ms | 13.73
| getChannelMembersForTeamForUser | p99 | 24ms | 27ms | 3ms | 12.30
| getChannelsForTeamForUser | p99 | 25ms | 28ms | 3ms | 12.05
| getProfileImage | p99 | 416ms | 464ms | 48ms | 11.53
| getThreadsForUser | p99 | 26ms | 29ms | 3ms | 11.47
| getUser | p99 | 45ms | 48ms | 3ms | 6.71
| viewChannel | p99 | 64ms | 68ms | 4ms | 6.25
| getPreferences | p99 | 32ms | 34ms | 2ms | 6.24
| getPublicChannelsForTeam | p99 | 69ms | 73ms | 4ms | 5.76
| getPostsForChannelAroundLastUnread | p99 | 166ms | 174ms | 8ms | 4.83
| searchGroupChannels | p99 | 42ms | 44ms | 2ms | 4.76
| updateCategoriesForTeamForUser | p99 | 237ms | 247ms | 10ms | 4.23
| getChannelMember | p99 | 75ms | 78ms | 3ms | 4.01
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -85.84
| setPostReminder | avg | 25ms | 17ms | -8ms | -32.44
| patchPost | avg | 40ms | 29ms | -11ms | -27.32
| getFileThumbnail | avg | 34ms | 28ms | -6ms | -17.67
| getFilePreview | avg | 40ms | 35ms | -5ms | -12.66
| removeUserCustomStatus | avg | 174ms | 160ms | -14ms | -8.04
| addChannelMember | avg | 245ms | 238ms | -7ms | -2.86
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| setPostReminder | p99 | 94ms | 25ms | -69ms | -73.78
| patchPost | p99 | 490ms | 228ms | -262ms | -53.47
| getChannel | p99 | 34ms | 24ms | -10ms | -29.52
| autocompleteUsers | p99 | 279ms | 206ms | -73ms | -26.12
| getChannelUnread | p99 | 23ms | 19ms | -4ms | -17.46
| saveReaction | p99 | 59ms | 49ms | -10ms | -16.84
| getPostThread | p99 | 69ms | 60ms | -9ms | -13.08
| createPost | p99 | 1.79s | 1.631s | -159ms | -8.88
| getChannelMembersForUser | p99 | 25ms | 23ms | -2ms | -8.15
| createGroupChannel | p99 | 960ms | 883ms | -77ms | -8.02
| getFilePreview | p99 | 160ms | 150ms | -10ms | -6.25
| getChannelsForUser | p99 | 37ms | 35ms | -2ms | -5.41
| getChannelStats | p99 | 50ms | 48ms | -2ms | -4.03
| getFileThumbnail | p99 | 98ms | 95ms | -3ms | -3.07
| login | p99 | 428ms | 417ms | -11ms | -2.57
| removeUserCustomStatus | p99 | 489ms | 478ms | -11ms | -2.25
| createDirectChannel | p99 | 499ms | 494ms | -5ms | -1.00
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 11.781
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 48.807
| |  P99| 5ms| 22ms | 17ms | 343.434
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.593
| ChannelStore.AnalyticsTypeCount |  Avg| 13ms| 8ms | -5ms | -37.936
| |  P99| 25ms| 10ms | -15ms | -60.307
| ChannelStore.Autocomplete |  Avg| 45ms| 44ms | -1ms | -2.232
| |  P99| 100ms| 100ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 85ms| 114ms | 29ms | 34.250
| |  P99| 3.28s| 3.792s | 512ms | 15.610
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 19ms | -2ms | -9.692
| |  P99| 93ms| 75ms | -18ms | -19.390
| ChannelStore.CreateInitialSidebarCategories |  Avg| 39ms| 41ms | 2ms | 5.080
| |  P99| 179ms| 199ms | 20ms | 11.200
| ChannelStore.Get |  Avg| 2ms| 3ms | 1ms | 40.377
| |  P99| 23ms| 24ms | 1ms | 4.322
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 12ms| 13ms | 1ms | 8.171
| |  P99| 25ms| 59ms | 34ms | 136.727
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 6ms | 5ms | 885.684
| |  P99| 10ms| 29ms | 19ms | 192.662
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 24ms| 30ms | 6ms | 24.941
| |  P99| 97ms| 354ms | 257ms | 264.649
| ChannelStore.GetByName |  Avg| 4ms| 5ms | 1ms | 22.297
| |  P99| 38ms| 44ms | 6ms | 15.721
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 0s | -2ms | -119.695
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.615
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 6ms | -9ms | -59.015
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.899
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 37ms | 4ms | 12.265
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 28ms | 4ms | 16.545
| ChannelStore.GetMemberCount |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 81ms| 81ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 5ms| 6ms | 1ms | 19.255
| |  P99| 20ms| 24ms | 4ms | 19.878
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.295
| ChannelStore.GetMembersForUserWithPagination |  Avg| 9ms| 8ms | -1ms | -11.708
| |  P99| 24ms| 23ms | -1ms | -4.155
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -56.693
| ChannelStore.GetPublicChannelsForTeam |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 69ms| 73ms | 4ms | 5.757
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 98ms| 99ms | 1ms | 1.019
| ChannelStore.GetSidebarCategory |  Avg| 15ms| 17ms | 2ms | 13.082
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 19ms| 21ms | 2ms | 10.288
| |  P99| 49ms| 50ms | 1ms | 2.051
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.552
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.004
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.006
| ChannelStore.Save |  Avg| 9ms| 11ms | 2ms | 23.223
| |  P99| 56ms| 82ms | 26ms | 46.428
| ChannelStore.SaveMember |  Avg| 32ms| 34ms | 2ms | 6.215
| |  P99| 175ms| 198ms | 23ms | 13.122
| ChannelStore.SearchGroupChannels |  Avg| 13ms| 14ms | 1ms | 7.826
| |  P99| 42ms| 44ms | 2ms | 4.758
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.014
| ChannelStore.UpdateSidebarCategories |  Avg| 54ms| 66ms | 12ms | 22.093
| |  P99| 99ms| 100ms | 1ms | 1.006
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 30ms | 18ms | 154.510
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 2ms| 1ms | -1ms | -62.847
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -39.091
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 15ms | -5ms | -24.484
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.127
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -22.174
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.866
| FileInfoStore.SetContent |  Avg| 7ms| 6ms | -1ms | -14.326
| |  P99| 40ms| 31ms | -9ms | -22.326
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 34ms | 9ms | 35.347
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.458
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 8ms | -13ms | -60.748
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 45ms | 17ms | 61.678
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 67ms | 29ms | 76.821
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 25ms | 7ms | 39.660
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -55.710
| JobStore.UpdateOptimistically |  Avg| 2ms| 4ms | 2ms | 87.203
| |  P99| 5ms| 39ms | 34ms | 686.869
| JobStore.UpdateStatus |  Avg| 3ms| 4ms | 1ms | 39.684
| |  P99| 5ms| 19ms | 14ms | 282.828
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.687
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.846
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.989
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 30ms | -5ms | -14.160
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 2ms | 1ms | 129.555
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -58.111
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.617
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 450ms| 0s | -450ms | -100.022
| |  P99| 498ms| 0s | -498ms | -100.101
| PostStore.Delete |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.871
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 29ms | 5ms | 20.558
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.539
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.231
| PostStore.GetPostReminderMetadata |  Avg| 4ms| 3ms | -1ms | -27.369
| |  P99| 21ms| 9ms | -12ms | -56.836
| PostStore.GetPostReminders |  Avg| 3ms| 5ms | 2ms | 62.916
| |  P99| 5ms| 22ms | 17ms | 343.434
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.092
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 127.908
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 73ms| 74ms | 1ms | 1.374
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -23.807
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 48ms| 62ms | 14ms | 28.939
| PostStore.SearchPostsForUser |  Avg| 167ms| 174ms | 7ms | 4.197
| |  P99| 2.328s| 2.336s | 8ms | 0.344
| PostStore.SetPostReminder |  Avg| 7ms| 4ms | -3ms | -42.096
| |  P99| 24ms| 10ms | -14ms | -58.269
| PostStore.Update |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 86ms | 37ms | 75.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 1ms | -1ms | -58.233
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.549
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 31ms | 1ms | 3.304
| PreferenceStore.Save |  Avg| 8ms| 9ms | 1ms | 11.938
| |  P99| 73ms| 80ms | 7ms | 9.548
| ProductNoticesStore.ClearOldNotices |  Avg| 65ms| 0s | -65ms | -99.895
| |  P99| 100ms| 0s | -100ms | -100.503
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 31ms| 32ms | 1ms | 3.241
| |  P99| 224ms| 233ms | 9ms | 4.024
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 12ms | -10ms | -44.621
| RoleStore.ChannelHigherScopedPermissions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 39ms | 16ms | 68.297
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 57ms | 7ms | 13.898
| SessionStore.GetLRUSessions |  Avg| 3ms| 0s | -3ms | -111.961
| |  P99| 23ms| 0s | -23ms | -101.039
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 19.381
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.781
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 41ms| 45ms | 4ms | 9.848
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.608
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 22ms | 6ms | 37.283
| StatusStore.SaveOrUpdate |  Avg| 64ms| 76ms | 12ms | 18.855
| |  P99| 812ms| 896ms | 84ms | 10.348
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 2ms | 1ms | 88.636
| |  P99| 5ms| 22ms | 17ms | 343.434
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.288
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.983
| TeamStore.AnalyticsTeamCount |  Avg| 6ms| 2ms | -4ms | -64.068
| |  P99| 25ms| 10ms | -15ms | -60.729
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.080
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 30ms | 6ms | 24.654
| TeamStore.GetByName |  Avg| 2ms| 0s | -2ms | -89.636
| |  P99| 25ms| 0s | -25ms | -100.201
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.105
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 76.917
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.900
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.247
| TeamStore.SaveMember |  Avg| 27ms| 28ms | 1ms | 3.646
| |  P99| 96ms| 109ms | 13ms | 13.577
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 30ms | -1ms | -3.227
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.042
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 31ms | 6ms | 24.087
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.098
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 26ms | 2ms | 8.393
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -39.682
| |  P99| 9ms| 19ms | 10ms | 116.281
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -88.193
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 42.688
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.746
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 25ms| 47ms | 22ms | 88.450
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 47ms | -2ms | -4.053
| |  P99| 353ms| 298ms | -55ms | -15.574
| UserStore.Count |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 89.246
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.366
| UserStore.GetAllProfilesInChannel |  Avg| 258ms| 263ms | 5ms | 1.938
| |  P99| 917ms| 923ms | 6ms | 0.654
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 44ms | 22ms | 100.917
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 3.971
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 46.585
| |  P99| 9ms| 23ms | 14ms | 153.006
| UserStore.GetProfileByIds |  Avg| 2ms| 3ms | 1ms | 40.241
| |  P99| 22ms| 23ms | 1ms | 4.472
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.955
| UserStore.GetProfilesInChannel |  Avg| 38ms| 35ms | -3ms | -7.868
| |  P99| 92ms| 50ms | -42ms | -45.653
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.148
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.492
| UserStore.Save |  Avg| 71ms| 72ms | 1ms | 1.405
| |  P99| 218ms| 221ms | 3ms | 1.376
| UserStore.Search |  Avg| 37ms| 36ms | -1ms | -2.739
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 8ms | 1ms | 13.701
| |  P99| 69ms| 44ms | -25ms | -36.386
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 33ms | 8ms | 32.379
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.240
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.154
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 40ms| 42ms | 2ms | 4.943
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 245ms| 238ms | -7ms | -2.860
| | P99| 494ms| 491ms | -3ms | -0.608
| addTeamMember | Avg| 848ms| 880ms | 32ms | 3.776
| | P99| 2.452s| 2.476s | 24ms | 0.979
| autocompleteChannelsForTeamForSearch | Avg| 85ms| 114ms | 29ms | 34.227
| | P99| 3.28s| 3.792s | 512ms | 15.610
| autocompleteUsers | Avg| 42ms| 41ms | -1ms | -2.367
| | P99| 279ms| 206ms | -73ms | -26.122
| createChannel | Avg| 20ms| 21ms | 1ms | 5.107
| | P99| 49ms| 50ms | 1ms | 2.051
| createDirectChannel | Avg| 229ms| 239ms | 10ms | 4.375
| | P99| 499ms| 494ms | -5ms | -1.003
| createGroupChannel | Avg| 336ms| 339ms | 3ms | 0.894
| | P99| 960ms| 883ms | -77ms | -8.021
| createPost | Avg| 312ms| 318ms | 6ms | 1.922
| | P99| 1.79s| 1.631s | -159ms | -8.885
| createUser | Avg| 101ms| 134ms | 33ms | 32.755
| | P99| 316ms| 477ms | 161ms | 50.976
| deletePost | Avg| 18ms| 17ms | -1ms | -5.597
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 4ms | 1ms | 29.707
| | P99| 30ms| 37ms | 7ms | 23.383
| getAnalytics | Avg| 36ms| 40ms | 4ms | 11.245
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 99ms| 100ms | 1ms | 1.014
| getChannel | Avg| 6ms| 5ms | -1ms | -17.064
| | P99| 34ms| 24ms | -10ms | -29.521
| getChannelMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 75ms| 78ms | 3ms | 4.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 27ms | 3ms | 12.300
| getChannelMembersForUser | Avg| 10ms| 9ms | -1ms | -10.029
| | P99| 25ms| 23ms | -2ms | -8.147
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 50ms| 48ms | -2ms | -4.031
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 19ms | -4ms | -17.459
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 28ms | 3ms | 12.049
| getChannelsForUser | Avg| 3ms| 4ms | 1ms | 28.847
| | P99| 37ms| 35ms | -2ms | -5.406
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 64ms| 73ms | 9ms | 14.107
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 40ms| 35ms | -5ms | -12.658
| | P99| 160ms| 150ms | -10ms | -6.251
| getFileThumbnail | Avg| 34ms| 28ms | -6ms | -17.669
| | P99| 98ms| 95ms | -3ms | -3.065
| getFilteredUsersStats | Avg| 13ms| 14ms | 1ms | 7.527
| | P99| 25ms| 25ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 56ms| 64ms | 8ms | 14.308
| | P99| 99ms| 99ms | 0s | 0.000
| getPostThread | Avg| 12ms| 11ms | -1ms | -8.665
| | P99| 69ms| 60ms | -9ms | -13.080
| getPostsForChannel | Avg| 26ms| 25ms | -1ms | -3.904
| | P99| 221ms| 220ms | -1ms | -0.453
| getPostsForChannelAroundLastUnread | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 166ms| 174ms | 8ms | 4.831
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 32ms| 34ms | 2ms | 6.235
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 79ms| 88ms | 9ms | 11.328
| | P99| 416ms| 464ms | 48ms | 11.531
| getPublicChannelsForTeam | Avg| 21ms| 20ms | -1ms | -4.863
| | P99| 69ms| 73ms | 4ms | 5.757
| getRolesByNames | Avg| 0s| 1ms | 1ms | 1084.035
| | P99| 5ms| 10ms | 5ms | 100.948
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 23ms | 4ms | 21.443
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 36ms| 41ms | 5ms | 13.726
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 26ms| 25ms | -1ms | -3.851
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 46ms| 46ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 26ms| 29ms | 3ms | 11.467
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 45ms| 48ms | 3ms | 6.715
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 47ms| 47ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 71ms| 71ms | 0s | 0.000
| | P99| 428ms| 417ms | -11ms | -2.567
| logout | Avg| 50ms| 49ms | -1ms | -2.014
| | P99| 98ms| 97ms | -1ms | -1.022
| patchPost | Avg| 40ms| 29ms | -11ms | -27.322
| | P99| 490ms| 228ms | -262ms | -53.470
| removeUserCustomStatus | Avg| 174ms| 160ms | -14ms | -8.044
| | P99| 489ms| 478ms | -11ms | -2.249
| root | Avg| 0s| 1ms | 1ms | 773.844
| | P99| 5ms| 9ms | 4ms | 80.808
| saveReaction | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 59ms| 49ms | -10ms | -16.840
| searchAllChannels | Avg| 45ms| 44ms | -1ms | -2.219
| | P99| 100ms| 100ms | 0s | 0.000
| searchGroupChannels | Avg| 13ms| 14ms | 1ms | 7.787
| | P99| 42ms| 44ms | 2ms | 4.758
| searchPostsInTeam | Avg| 175ms| 182ms | 7ms | 4.004
| | P99| 2.346s| 2.345s | -1ms | -0.043
| searchUsers | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 25ms| 17ms | -8ms | -32.435
| | P99| 94ms| 25ms | -69ms | -73.779
| unfollowThreadByUser | Avg| 12ms| 11ms | -1ms | -8.655
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 87ms| 102ms | 15ms | 17.145
| | P99| 237ms| 247ms | 10ms | 4.227
| updatePreferences | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -85.843
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 131ms| 182ms | 51ms | 39.015
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 376ms| 390ms | 14ms | 3.724
| | P99| 987ms| 988ms | 1ms | 0.101
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 64ms| 68ms | 4ms | 6.253
