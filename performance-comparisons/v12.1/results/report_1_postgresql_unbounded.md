### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 1ms | 68ms | 67ms | 9173.99
| UserAccessTokenStore.GetExpiringTokens | avg | 1ms | 64ms | 63ms | 5090.61
| UserAccessTokenStore.GetExpiredBefore | avg | 2ms | 56ms | 54ms | 3182.55
| RoleStore.ChannelHigherScopedPermissions | avg | 4ms | 30ms | 26ms | 642.52
| PropertyFieldStore.GetForGroup | avg | 8ms | 58ms | 50ms | 617.09
| ChannelStore.GetMembers | avg | 3ms | 8ms | 5ms | 159.61
| PreferenceStore.DeleteCategoryAndName | avg | 3ms | 6ms | 3ms | 111.43
| TokenStore.Cleanup | avg | 2ms | 4ms | 2ms | 109.70
| RoleStore.GetByNames | avg | 5ms | 10ms | 5ms | 95.06
| SessionStore.GetSessionsExpired | avg | 3ms | 5ms | 2ms | 65.16
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 6ms | 9ms | 3ms | 49.43
| JobStore.UpdateStatusOptimistically | avg | 4ms | 6ms | 2ms | 48.96
| ClusterDiscoveryStore.SetLastPingAt | avg | 4ms | 6ms | 2ms | 46.93
| PostStore.SetPostReminder | avg | 10ms | 14ms | 4ms | 39.38
| TeamStore.GetTotalMemberCount | avg | 28ms | 34ms | 6ms | 21.23
| ChannelStore.GetSidebarCategory | avg | 12ms | 14ms | 2ms | 16.30
| ChannelStore.GetTeamChannels | avg | 41ms | 47ms | 6ms | 14.51
| ChannelStore.AutocompleteInTeamForSearch | avg | 43ms | 47ms | 4ms | 9.32
| ChannelStore.UpdateSidebarCategories | avg | 49ms | 53ms | 4ms | 8.09
| TeamStore.GetActiveMemberCount | avg | 36ms | 38ms | 2ms | 5.49
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserAccessTokenStore.GetExpiredBefore | p99 | 5ms | 100ms | 95ms | 1919.19
| UserAccessTokenStore.GetExpiringTokens | p99 | 5ms | 100ms | 95ms | 1919.19
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 100ms | 95ms | 1919.19
| PropertyFieldStore.GetForGroup | p99 | 43ms | 325ms | 282ms | 655.81
| ChannelStore.GetMembers | p99 | 5ms | 24ms | 19ms | 383.84
| JobStore.GetCountByStatusAndType | p99 | 25ms | 98ms | 73ms | 293.76
| RoleStore.ChannelHigherScopedPermissions | p99 | 26ms | 99ms | 73ms | 286.27
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 75ms | 183ms | 108ms | 144.00
| PreferenceStore.DeleteCategoryAndName | p99 | 75ms | 183ms | 108ms | 144.00
| TokenStore.Cleanup | p99 | 10ms | 24ms | 14ms | 142.85
| ChannelStore.GetTeamChannels | p99 | 95ms | 225ms | 130ms | 136.35
| SessionStore.GetSessionsExpired | p99 | 23ms | 47ms | 24ms | 103.45
| ClusterDiscoveryStore.SetLastPingAt | p99 | 49ms | 99ms | 50ms | 101.27
| EmojiStore.GetMultipleByName | p99 | 5ms | 10ms | 5ms | 101.01
| RoleStore.GetByNames | p99 | 46ms | 91ms | 45ms | 98.54
| UserStore.GetMany | p99 | 43ms | 84ms | 41ms | 95.91
| TeamStore.GetTotalMemberCount | p99 | 50ms | 97ms | 47ms | 94.74
| TemporaryPostStore.GetExpiredPosts | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetSidebarCategory | p99 | 107ms | 184ms | 77ms | 71.63
| FileInfoStore.AttachToPost | p99 | 52ms | 85ms | 33ms | 63.87
| ThreadStore.Get | p99 | 31ms | 49ms | 18ms | 57.91
| JobStore.UpdateStatusOptimistically | p99 | 51ms | 74ms | 23ms | 45.41
| PostStore.Update | p99 | 96ms | 138ms | 42ms | 43.98
| ChannelStore.UpdateSidebarCategories | p99 | 370ms | 530ms | 160ms | 43.24
| FileInfoStore.SetContent | p99 | 96ms | 137ms | 41ms | 42.58
| SessionStore.Remove | p99 | 19ms | 23ms | 4ms | 21.05
| UserStore.Update | p99 | 183ms | 212ms | 29ms | 15.83
| ChannelStore.GetMemberForPost | p99 | 100ms | 114ms | 14ms | 14.02
| PostStore.SetPostReminder | p99 | 175ms | 199ms | 24ms | 13.71
| JobStore.Save | p99 | 22ms | 25ms | 3ms | 13.69
| ChannelStore.AutocompleteInTeamForSearch | p99 | 492ms | 556ms | 64ms | 13.01
| ChannelStore.SearchGroupChannels | p99 | 87ms | 95ms | 8ms | 9.21
| StatusStore.Get | p99 | 46ms | 50ms | 4ms | 8.68
| ChannelStore.GetMany | p99 | 156ms | 165ms | 9ms | 5.79
| ChannelStore.Get | p99 | 151ms | 156ms | 5ms | 3.31
| TeamStore.GetActiveMemberCount | p99 | 93ms | 96ms | 3ms | 3.23
| JobStore.GetAllByStatus | p99 | 85ms | 87ms | 2ms | 2.36
| ChannelStore.GetForPost | p99 | 88ms | 90ms | 2ms | 2.27
| StatusStore.SaveOrUpdateMany | p99 | 195ms | 197ms | 2ms | 1.03
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.GetPostsByIds | avg | 3ms | 0s | -3ms | -119.27
| ChannelStore.GetChannelsByIds | avg | 3ms | 0s | -3ms | -119.23
| PostPersistentNotificationStore.UpdateLastActivity | avg | 6ms | 0s | -6ms | -103.20
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | avg | 3ms | 0s | -3ms | -93.84
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 12ms | 4ms | -8ms | -66.73
| PropertyGroupStore.Get | avg | 6ms | 2ms | -4ms | -64.62
| ScheduledPostStore.GetPendingScheduledPosts | avg | 13ms | 6ms | -7ms | -54.50
| ChannelStore.CreateSidebarCategory | avg | 40ms | 18ms | -22ms | -54.38
| UserStore.GetByUsername | avg | 7ms | 4ms | -3ms | -44.59
| StatusStore.UpdateExpiredDNDStatuses | avg | 5ms | 3ms | -2ms | -41.24
| ThreadStore.MarkAllAsReadByTeam | avg | 12ms | 7ms | -5ms | -40.40
| BotStore.Get | avg | 8ms | 5ms | -3ms | -39.92
| PluginStore.List | avg | 6ms | 4ms | -2ms | -31.98
| ChannelStore.GetChannelUnread | avg | 7ms | 5ms | -2ms | -29.51
| ProductNoticesStore.ClearOldNotices | avg | 8ms | 6ms | -2ms | -23.82
| PostStore.SearchPostsForUser | avg | 620ms | 539ms | -81ms | -13.07
| PostStore.AnalyticsPostCount | avg | 426ms | 376ms | -50ms | -11.73
| ChannelStore.CreateDirectChannel | avg | 35ms | 31ms | -4ms | -11.45
| ChannelStore.GetPublicChannelsForTeam | avg | 47ms | 45ms | -2ms | -4.29
| UserStore.Save | avg | 132ms | 130ms | -2ms | -1.52
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 10ms | 0s | -10ms | -100.50
| PropertyGroupStore.Get | p99 | 85ms | 10ms | -75ms | -88.24
| ChannelStore.CreateSidebarCategory | p99 | 241ms | 49ms | -192ms | -79.67
| BotStore.Get | p99 | 203ms | 46ms | -157ms | -77.15
| PostPersistentNotificationStore.Get | p99 | 37ms | 9ms | -28ms | -75.60
| StatusStore.UpdateExpiredDNDStatuses | p99 | 134ms | 43ms | -91ms | -68.04
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 10ms | -15ms | -60.70
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 203ms | 84ms | -119ms | -58.48
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 203ms | 84ms | -119ms | -58.48
| PluginStore.List | p99 | 157ms | 69ms | -88ms | -56.05
| UserStore.GetByUsername | p99 | 98ms | 46ms | -52ms | -53.12
| ThreadStore.MarkAllAsReadByChannels | p99 | 48ms | 23ms | -25ms | -51.88
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 24ms | -25ms | -50.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 50ms | 25ms | -25ms | -50.40
| PostStore.Delete | p99 | 175ms | 93ms | -82ms | -46.86
| UserStore.IsEmpty | p99 | 36ms | 25ms | -11ms | -30.92
| ChannelStore.GetChannelUnread | p99 | 95ms | 68ms | -27ms | -28.30
| ThreadStore.UpdateMembership | p99 | 33ms | 25ms | -8ms | -24.17
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 14ms | 11ms | -3ms | -22.08
| FileInfoStore.GetByIds | p99 | 64ms | 50ms | -14ms | -21.95
| ThreadStore.MarkAsRead | p99 | 33ms | 26ms | -7ms | -21.21
| TeamStore.GetMember | p99 | 19ms | 15ms | -4ms | -20.57
| ThreadStore.GetThreadUnreadReplyCount | p99 | 62ms | 50ms | -12ms | -19.46
| ThreadStore.GetThreadForUser | p99 | 64ms | 52ms | -12ms | -18.82
| UserAccessTokenStore.GetByToken | p99 | 45ms | 37ms | -8ms | -17.93
| SessionStore.Save | p99 | 34ms | 28ms | -6ms | -17.90
| PostStore.GetPostsAfter | p99 | 17ms | 14ms | -3ms | -17.53
| ThreadStore.GetThreadFollowers | p99 | 35ms | 29ms | -6ms | -17.33
| ChannelStore.GetByName | p99 | 24ms | 20ms | -4ms | -16.80
| ChannelStore.CreateDirectChannel | p99 | 388ms | 332ms | -56ms | -14.44
| PropertyValueStore.SearchPropertyValues | p99 | 15ms | 13ms | -2ms | -13.69
| ThreadStore.GetTotalUnreadMentions | p99 | 33ms | 29ms | -4ms | -12.27
| ChannelStore.GetPublicChannelsForTeam | p99 | 208ms | 183ms | -25ms | -11.99
| PostAcknowledgementStore.GetForPost | p99 | 27ms | 24ms | -3ms | -11.32
| SessionStore.Get | p99 | 55ms | 49ms | -6ms | -10.92
| PostStore.GetPostReminderMetadata | p99 | 75ms | 67ms | -8ms | -10.60
| PostPriorityStore.GetForPostWithContext | p99 | 29ms | 26ms | -3ms | -10.17
| ChannelStore.CreateInitialSidebarCategories | p99 | 296ms | 267ms | -29ms | -9.79
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 32ms | 29ms | -3ms | -9.36
| LinkMetadataStore.Save | p99 | 69ms | 63ms | -6ms | -8.67
| TeamStore.Get | p99 | 37ms | 34ms | -3ms | -8.19
| WebhookStore.GetOutgoingByTeam | p99 | 74ms | 68ms | -6ms | -8.08
| UserStore.GetProfileByIds | p99 | 104ms | 96ms | -8ms | -7.69
| PostStore.GetSingle | p99 | 40ms | 37ms | -3ms | -7.52
| PreferenceStore.GetAll | p99 | 40ms | 37ms | -3ms | -7.43
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 85ms | 79ms | -6ms | -7.07
| DraftStore.Delete | p99 | 74ms | 69ms | -5ms | -6.76
| PostStore.GetPostsByThread | p99 | 45ms | 42ms | -3ms | -6.63
| EmojiStore.GetByName | p99 | 63ms | 59ms | -4ms | -6.35
| PostStore.Get | p99 | 133ms | 125ms | -8ms | -6.00
| PostStore.GetPosts | p99 | 68ms | 64ms | -4ms | -5.89
| ScheduledPostStore.CreateScheduledPost | p99 | 87ms | 82ms | -5ms | -5.74
| PreferenceStore.Get | p99 | 57ms | 54ms | -3ms | -5.30
| ChannelStore.GetChannelsByUser | p99 | 39ms | 37ms | -2ms | -5.16
| UserStore.Save | p99 | 443ms | 421ms | -22ms | -4.97
| ThreadStore.GetTeamsUnreadForUser | p99 | 42ms | 40ms | -2ms | -4.78
| ChannelStore.UpdateLastViewedAt | p99 | 42ms | 40ms | -2ms | -4.77
| ChannelStore.SaveMember | p99 | 64ms | 61ms | -3ms | -4.69
| GroupStore.GetByName | p99 | 65ms | 62ms | -3ms | -4.60
| LinkMetadataStore.Get | p99 | 45ms | 43ms | -2ms | -4.46
| PostAcknowledgementStore.GetForPosts | p99 | 45ms | 43ms | -2ms | -4.44
| ChannelStore.Save | p99 | 214ms | 205ms | -9ms | -4.20
| GroupStore.GetGroups | p99 | 48ms | 46ms | -2ms | -4.19
| StatusStore.SaveOrUpdate | p99 | 74ms | 71ms | -3ms | -4.06
| ChannelStore.GetBoardChannel | p99 | 75ms | 72ms | -3ms | -4.02
| PostPriorityStore.GetForPosts | p99 | 50ms | 48ms | -2ms | -4.01
| ChannelStore.GetGuestCount | p99 | 52ms | 50ms | -2ms | -3.87
| PostStore.GetEtag | p99 | 78ms | 75ms | -3ms | -3.85
| ChannelStore.GetMembersForUser | p99 | 82ms | 79ms | -3ms | -3.66
| ThreadStore.MaintainMembership | p99 | 62ms | 60ms | -2ms | -3.22
| DraftStore.Upsert | p99 | 94ms | 91ms | -3ms | -3.19
| ChannelStore.GetMemberCount | p99 | 70ms | 68ms | -2ms | -2.85
| FileInfoStore.Get | p99 | 70ms | 68ms | -2ms | -2.84
| UserStore.GetProfilesByUsernames | p99 | 75ms | 73ms | -2ms | -2.67
| ChannelStore.GetMemberLastViewedAt | p99 | 78ms | 76ms | -2ms | -2.56
| ChannelStore.GetAllChannelMembersForUser | p99 | 79ms | 77ms | -2ms | -2.53
| FileInfoStore.Save | p99 | 80ms | 78ms | -2ms | -2.49
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | avg | 13ms | 37ms | 24ms | 185.32
| getChannelMembers | avg | 5ms | 10ms | 5ms | 111.03
| setPostReminder | avg | 42ms | 52ms | 10ms | 23.82
| updateCategoriesForTeamForUser | avg | 78ms | 91ms | 13ms | 16.61
| getTeamStats | avg | 37ms | 42ms | 5ms | 13.44
| logout | avg | 62ms | 70ms | 8ms | 12.80
| autocompleteChannelsForTeamForSearch | avg | 44ms | 47ms | 3ms | 6.86
| getPostsForChannelAroundLastUnread | avg | 134ms | 142ms | 8ms | 5.98
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 46ms | 459ms | 413ms | 902.73
| getChannelMembers | p99 | 10ms | 49ms | 39ms | 397.96
| getChannel | p99 | 113ms | 170ms | 57ms | 50.67
| root | p99 | 17ms | 23ms | 6ms | 34.88
| updateCategoriesForTeamForUser | p99 | 435ms | 530ms | 95ms | 21.84
| autocompleteChannelsForTeamForSearch | p99 | 493ms | 556ms | 63ms | 12.79
| searchGroupChannels | p99 | 87ms | 97ms | 10ms | 11.44
| setPostReminder | p99 | 375ms | 415ms | 40ms | 10.67
| getPostsForChannelAroundLastUnread | p99 | 6.058s | 6.464s | 406ms | 6.70
| getTeamStats | p99 | 93ms | 98ms | 5ms | 5.38
| unfollowThreadByUser | p99 | 261ms | 274ms | 13ms | 4.98
| upsertDraft | p99 | 105ms | 109ms | 4ms | 3.81
| deletePost | p99 | 375ms | 388ms | 13ms | 3.47
| getUsers | p99 | 160ms | 163ms | 3ms | 1.87
| login | p99 | 434ms | 440ms | 6ms | 1.38
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteScheduledPost | avg | 6ms | 0s | -6ms | -98.54
| createCategoryForTeamForUser | avg | 62ms | 24ms | -38ms | -60.81
| getProfileImage | avg | 43ms | 20ms | -23ms | -53.44
| updateReadStateAllThreadsByUser | avg | 13ms | 7ms | -6ms | -46.80
| getChannelUnread | avg | 8ms | 5ms | -3ms | -39.83
| patchPost | avg | 46ms | 31ms | -15ms | -32.80
| createChannel | avg | 982ms | 682ms | -300ms | -30.53
| searchPostsInAllTeams | avg | 1.104s | 838ms | -266ms | -24.09
| addChannelMember | avg | 836ms | 730ms | -106ms | -12.67
| deletePost | avg | 33ms | 29ms | -4ms | -12.18
| removeUserCustomStatus | avg | 871ms | 786ms | -85ms | -9.76
| updateReadStateThreadByUser | avg | 48ms | 45ms | -3ms | -6.28
| searchPostsInTeam | avg | 422ms | 410ms | -12ms | -2.85
| uploadFileStream | avg | 468ms | 455ms | -13ms | -2.78
| createGroupChannel | avg | 2.205s | 2.151s | -54ms | -2.45
| createUser | avg | 152ms | 149ms | -3ms | -1.98
| createPost | avg | 155ms | 153ms | -2ms | -1.29
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteScheduledPost | p99 | 10ms | 0s | -10ms | -100.50
| createCategoryForTeamForUser | p99 | 485ms | 50ms | -435ms | -89.69
| getProfileImage | p99 | 314ms | 140ms | -174ms | -55.47
| updateReadStateAllThreadsByUser | p99 | 49ms | 24ms | -25ms | -50.89
| createGroupChannel | p99 | 8.425s | 4.937s | -3.488s | -41.40
| getChannelUnread | p99 | 120ms | 76ms | -44ms | -36.59
| patchPost | p99 | 416ms | 285ms | -131ms | -31.52
| uploadFileStream | p99 | 1.198s | 997ms | -201ms | -16.78
| getConfig | p99 | 171ms | 145ms | -26ms | -15.19
| getChannelsForUser | p99 | 147ms | 130ms | -17ms | -11.60
| getAllTeams | p99 | 27ms | 24ms | -3ms | -11.30
| getTeamsUnreadForUser | p99 | 62ms | 56ms | -6ms | -9.71
| updateReadStateThreadByUser | p99 | 407ms | 372ms | -35ms | -8.61
| getClientConfig | p99 | 53ms | 49ms | -4ms | -7.59
| getTeamMember | p99 | 70ms | 65ms | -5ms | -7.16
| getPublicChannelsForTeam | p99 | 211ms | 196ms | -15ms | -7.09
| getUser | p99 | 46ms | 43ms | -3ms | -6.55
| createSchedulePost | p99 | 87ms | 82ms | -5ms | -5.74
| getPreferences | p99 | 41ms | 39ms | -2ms | -4.84
| getTeamScheduledPosts | p99 | 43ms | 41ms | -2ms | -4.67
| getChannelStats | p99 | 47ms | 45ms | -2ms | -4.30
| getCategoriesForTeamForUser | p99 | 164ms | 160ms | -4ms | -2.43
| getChannelMembersForTeamForUser | p99 | 86ms | 84ms | -2ms | -2.33
| getThreadsForUser | p99 | 87ms | 85ms | -2ms | -2.30
| getFilePreview | p99 | 228ms | 223ms | -5ms | -2.20
| getFileThumbnail | p99 | 218ms | 214ms | -4ms | -1.83
| createDirectChannel | p99 | 4.776s | 4.691s | -85ms | -1.78
| saveReaction | p99 | 231ms | 227ms | -4ms | -1.73
| searchPostsInTeam | p99 | 8.609s | 8.464s | -145ms | -1.68
| searchUsers | p99 | 134ms | 132ms | -2ms | -1.49
| createUser | p99 | 480ms | 474ms | -6ms | -1.25
| getPostsForChannel | p99 | 462ms | 457ms | -5ms | -1.08
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 37ms | 0s | 0.000
| BotStore.Get |  Avg| 8ms| 5ms | -3ms | -39.916
| |  P99| 203ms| 46ms | -157ms | -77.150
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -22.083
| ChannelStore.Autocomplete |  Avg| 412ms| 416ms | 4ms | 0.971
| |  P99| 990ms| 991ms | 1ms | 0.101
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 43ms| 47ms | 4ms | 9.316
| |  P99| 492ms| 556ms | 64ms | 13.008
| ChannelStore.CreateDirectChannel |  Avg| 35ms| 31ms | -4ms | -11.450
| |  P99| 388ms| 332ms | -56ms | -14.438
| ChannelStore.CreateInitialSidebarCategories |  Avg| 39ms| 38ms | -1ms | -2.571
| |  P99| 296ms| 267ms | -29ms | -9.789
| ChannelStore.CreateSidebarCategory |  Avg| 40ms| 18ms | -22ms | -54.381
| |  P99| 241ms| 49ms | -192ms | -79.668
| ChannelStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 151ms| 156ms | 5ms | 3.305
| ChannelStore.GetAllChannelMembersForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 77ms | -2ms | -2.527
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 12ms | -1ms | -7.921
| |  P99| 85ms| 79ms | -6ms | -7.073
| ChannelStore.GetBoardChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 75ms| 72ms | -3ms | -4.016
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 20ms | -4ms | -16.798
| ChannelStore.GetChannelUnread |  Avg| 7ms| 5ms | -2ms | -29.512
| |  P99| 95ms| 68ms | -27ms | -28.302
| ChannelStore.GetChannels |  Avg| 8ms| 7ms | -1ms | -13.240
| |  P99| 87ms| 87ms | 0s | 0.000
| ChannelStore.GetChannelsByIds |  Avg| 3ms| 0s | -3ms | -119.234
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 37ms | -2ms | -5.156
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.091
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 63ms| 63ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.272
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 52ms| 50ms | -2ms | -3.872
| ChannelStore.GetMany |  Avg| 9ms| 10ms | 1ms | 10.782
| |  P99| 156ms| 165ms | 9ms | 5.788
| ChannelStore.GetMember |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 97ms| 97ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 70ms| 68ms | -2ms | -2.847
| ChannelStore.GetMemberForPost |  Avg| 27ms| 26ms | -1ms | -3.773
| |  P99| 100ms| 114ms | 14ms | 14.018
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 78ms| 76ms | -2ms | -2.564
| ChannelStore.GetMembers |  Avg| 3ms| 8ms | 5ms | 159.607
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelStore.GetMembersForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 79ms | -3ms | -3.662
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.092
| ChannelStore.GetPinnedPostCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.142
| ChannelStore.GetPublicChannelsForTeam |  Avg| 47ms| 45ms | -2ms | -4.286
| |  P99| 208ms| 183ms | -25ms | -11.993
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 5ms | -1ms | -18.023
| |  P99| 32ms| 29ms | -3ms | -9.365
| ChannelStore.GetSidebarCategory |  Avg| 12ms| 14ms | 2ms | 16.298
| |  P99| 107ms| 184ms | 77ms | 71.632
| ChannelStore.GetTeamChannels |  Avg| 41ms| 47ms | 6ms | 14.506
| |  P99| 95ms| 225ms | 130ms | 136.353
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.034
| ChannelStore.Save |  Avg| 18ms| 17ms | -1ms | -5.522
| |  P99| 214ms| 205ms | -9ms | -4.200
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 64ms| 61ms | -3ms | -4.687
| ChannelStore.SearchGroupChannels |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 87ms| 95ms | 8ms | 9.212
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 4ms | -1ms | -21.733
| |  P99| 42ms| 40ms | -2ms | -4.772
| ChannelStore.UpdateSidebarCategories |  Avg| 49ms| 53ms | 4ms | 8.094
| |  P99| 370ms| 530ms | 160ms | 43.244
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 35ms| 36ms | 1ms | 2.890
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 6ms | 2ms | 46.934
| |  P99| 49ms| 99ms | 50ms | 101.266
| CommandWebhookStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -54.478
| |  P99| 10ms| 5ms | -5ms | -51.020
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 68ms | 67ms | 9173.985
| |  P99| 5ms| 100ms | 95ms | 1919.192
| DraftStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 74ms| 69ms | -5ms | -6.758
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 6ms| 9ms | 3ms | 49.430
| |  P99| 75ms| 183ms | 108ms | 144.002
| DraftStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 92ms| 91ms | -1ms | -1.090
| DraftStore.GetDraftsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 92ms| 92ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 8ms| 7ms | -1ms | -12.949
| |  P99| 94ms| 91ms | -3ms | -3.185
| EmojiStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 63ms| 59ms | -4ms | -6.349
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 52ms| 85ms | 33ms | 63.869
| FileInfoStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 70ms| 68ms | -2ms | -2.845
| FileInfoStore.GetByIds |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 64ms| 50ms | -14ms | -21.949
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| FileInfoStore.GetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 78ms | -2ms | -2.488
| FileInfoStore.SetContent |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 137ms | 41ms | 42.576
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 5ms| 4ms | -1ms | -21.959
| |  P99| 65ms| 62ms | -3ms | -4.600
| GroupStore.GetGroups |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.189
| JobStore.GetAllByStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 85ms| 87ms | 2ms | 2.360
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 4ms | 1ms | 37.681
| |  P99| 25ms| 98ms | 73ms | 293.763
| JobStore.GetNewestJobByStatusesAndType |  Avg| 4ms| 3ms | -1ms | -23.607
| |  P99| 50ms| 25ms | -25ms | -50.403
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 30.308
| |  P99| 22ms| 25ms | 3ms | 13.692
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 30.035
| |  P99| 37ms| 37ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 6ms | 2ms | 48.960
| |  P99| 51ms| 74ms | 23ms | 45.415
| LinkMetadataStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.459
| LinkMetadataStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 69ms| 63ms | -6ms | -8.669
| PluginStore.List |  Avg| 6ms| 4ms | -2ms | -31.983
| |  P99| 157ms| 69ms | -88ms | -56.051
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -36.639
| |  P99| 27ms| 24ms | -3ms | -11.316
| PostAcknowledgementStore.GetForPosts |  Avg| 4ms| 3ms | -1ms | -26.698
| |  P99| 45ms| 43ms | -2ms | -4.439
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 2ms | 1ms | 68.284
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 37ms| 9ms | -28ms | -75.603
| PostPersistentNotificationStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 6ms| 0s | -6ms | -103.200
| |  P99| 10ms| 0s | -10ms | -100.503
| PostPriorityStore.GetForPostWithContext |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 29ms| 26ms | -3ms | -10.172
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 50ms| 48ms | -2ms | -4.014
| PostStore.AnalyticsPostCount |  Avg| 426ms| 376ms | -50ms | -11.728
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 16ms| 15ms | -1ms | -6.193
| |  P99| 175ms| 93ms | -82ms | -46.858
| PostStore.Get |  Avg| 9ms| 8ms | -1ms | -11.419
| |  P99| 133ms| 125ms | -8ms | -5.997
| PostStore.GetEtag |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 78ms| 75ms | -3ms | -3.850
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 9ms| 8ms | -1ms | -11.142
| |  P99| 75ms| 67ms | -8ms | -10.596
| PostStore.GetPostReminders |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 68ms| 64ms | -4ms | -5.892
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.535
| PostStore.GetPostsBefore |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.163
| PostStore.GetPostsByIds |  Avg| 3ms| 0s | -3ms | -119.269
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 5ms| 4ms | -1ms | -21.770
| |  P99| 45ms| 42ms | -3ms | -6.629
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.112
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.520
| PostStore.GetVisiblePostIdAroundTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 38ms | -1ms | -2.542
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 227ms| 226ms | -1ms | -0.441
| PostStore.SearchPostsForUser |  Avg| 620ms| 539ms | -81ms | -13.067
| |  P99| 10s| 10s | 0s | 0.000
| PostStore.SetPostReminder |  Avg| 10ms| 14ms | 4ms | 39.377
| |  P99| 175ms| 199ms | 24ms | 13.714
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 96ms| 138ms | 42ms | 43.979
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 6ms | 3ms | 111.426
| |  P99| 75ms| 183ms | 108ms | 144.002
| PreferenceStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 57ms| 54ms | -3ms | -5.301
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.429
| PreferenceStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 152ms| 153ms | 1ms | 0.658
| ProductNoticesStore.ClearOldNotices |  Avg| 8ms| 6ms | -2ms | -23.818
| |  P99| 25ms| 10ms | -15ms | -60.699
| PropertyFieldStore.GetForGroup |  Avg| 8ms| 58ms | 50ms | 617.094
| |  P99| 43ms| 325ms | 282ms | 655.814
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.628
| PropertyGroupStore.Get |  Avg| 6ms| 2ms | -4ms | -64.618
| |  P99| 85ms| 10ms | -75ms | -88.235
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.692
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.110
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 30ms | 26ms | 642.520
| |  P99| 26ms| 99ms | 73ms | 286.275
| RoleStore.GetByNames |  Avg| 5ms| 10ms | 5ms | 95.059
| |  P99| 46ms| 91ms | 45ms | 98.540
| ScheduledPostStore.CreateScheduledPost |  Avg| 7ms| 8ms | 1ms | 14.371
| |  P99| 87ms| 82ms | -5ms | -5.736
| ScheduledPostStore.Get |  Avg| 1ms| 0s | -1ms | -80.211
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 13ms| 6ms | -7ms | -54.497
| |  P99| 203ms| 84ms | -119ms | -58.477
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ScheduledPostStore.PermanentlyDeleteScheduledPosts |  Avg| 3ms| 0s | -3ms | -93.836
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 12ms| 4ms | -8ms | -66.730
| |  P99| 203ms| 84ms | -119ms | -58.477
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 55ms| 49ms | -6ms | -10.925
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 3ms| 5ms | 2ms | 65.165
| |  P99| 23ms| 47ms | 24ms | 103.453
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 4ms| 3ms | -1ms | -28.092
| |  P99| 36ms| 36ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 23ms | 4ms | 21.052
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 34ms| 28ms | -6ms | -17.896
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.224
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 46ms| 50ms | 4ms | 8.684
| StatusStore.GetByIds |  Avg| 7ms| 6ms | -1ms | -14.950
| |  P99| 93ms| 92ms | -1ms | -1.077
| StatusStore.SaveOrUpdate |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 74ms| 71ms | -3ms | -4.063
| StatusStore.SaveOrUpdateMany |  Avg| 12ms| 13ms | 1ms | 8.182
| |  P99| 195ms| 197ms | 2ms | 1.027
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 3ms | -2ms | -41.239
| |  P99| 134ms| 43ms | -91ms | -68.037
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.430
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| TeamStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 34ms | -3ms | -8.194
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 38ms | 2ms | 5.494
| |  P99| 93ms| 96ms | 3ms | 3.226
| TeamStore.GetAllPage |  Avg| 3ms| 2ms | -1ms | -38.567
| |  P99| 23ms| 22ms | -1ms | -4.378
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 4ms | -1ms | -21.460
| |  P99| 39ms| 38ms | -1ms | -2.534
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 15ms | -4ms | -20.570
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 3ms| 2ms | -1ms | -39.699
| |  P99| 22ms| 22ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 28ms| 34ms | 6ms | 21.226
| |  P99| 50ms| 97ms | 47ms | 94.737
| TeamStore.SaveMember |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TemporaryPostStore.GetExpiredPosts |  Avg| 1ms| 2ms | 1ms | 115.694
| |  P99| 5ms| 9ms | 4ms | 80.808
| ThreadStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 49ms | 18ms | 57.908
| ThreadStore.GetMembershipForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.079
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.781
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 35ms| 29ms | -6ms | -17.332
| ThreadStore.GetThreadForUser |  Avg| 7ms| 6ms | -1ms | -14.533
| |  P99| 64ms| 52ms | -12ms | -18.818
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 5ms | -1ms | -17.666
| |  P99| 62ms| 50ms | -12ms | -19.456
| ThreadStore.GetThreadsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.109
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.038
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 29ms | -4ms | -12.266
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.062
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.001
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 62ms| 60ms | -2ms | -3.218
| ThreadStore.MarkAllAsReadByChannels |  Avg| 4ms| 3ms | -1ms | -27.459
| |  P99| 48ms| 23ms | -25ms | -51.881
| ThreadStore.MarkAllAsReadByTeam |  Avg| 12ms| 7ms | -5ms | -40.402
| |  P99| 49ms| 24ms | -25ms | -50.891
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 26ms | -7ms | -21.209
| ThreadStore.UpdateMembership |  Avg| 4ms| 3ms | -1ms | -26.917
| |  P99| 33ms| 25ms | -8ms | -24.175
| TokenStore.Cleanup |  Avg| 2ms| 4ms | 2ms | 109.698
| |  P99| 10ms| 24ms | 14ms | 142.853
| UserAccessTokenStore.GetByToken |  Avg| 5ms| 4ms | -1ms | -21.464
| |  P99| 45ms| 37ms | -8ms | -17.927
| UserAccessTokenStore.GetExpiredBefore |  Avg| 2ms| 56ms | 54ms | 3182.547
| |  P99| 5ms| 100ms | 95ms | 1919.192
| UserAccessTokenStore.GetExpiringTokens |  Avg| 1ms| 64ms | 63ms | 5090.613
| |  P99| 5ms| 100ms | 95ms | 1919.192
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 198ms| 199ms | 1ms | 0.505
| UserStore.Count |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.138
| UserStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.169
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 71ms| 72ms | 1ms | 1.405
| |  P99| 467ms| 469ms | 2ms | 0.428
| UserStore.GetByUsername |  Avg| 7ms| 4ms | -3ms | -44.590
| |  P99| 98ms| 46ms | -52ms | -53.115
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 40ms | 1ms | 2.591
| UserStore.GetMany |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 84ms | 41ms | 95.907
| UserStore.GetProfileByIds |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 104ms| 96ms | -8ms | -7.692
| UserStore.GetProfilesByUsernames |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 75ms| 73ms | -2ms | -2.670
| UserStore.GetProfilesInChannel |  Avg| 94ms| 95ms | 1ms | 1.060
| |  P99| 231ms| 233ms | 2ms | 0.865
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.808
| UserStore.GetUnreadCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 25ms | -11ms | -30.918
| UserStore.Save |  Avg| 132ms| 130ms | -2ms | -1.518
| |  P99| 443ms| 421ms | -22ms | -4.968
| UserStore.Search |  Avg| 24ms| 23ms | -1ms | -4.234
| |  P99| 117ms| 116ms | -1ms | -0.857
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.Update |  Avg| 13ms| 14ms | 1ms | 7.810
| |  P99| 183ms| 212ms | 29ms | 15.825
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 33ms | 1ms | 3.088
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.841
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.239
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 6ms | -1ms | -14.534
| |  P99| 74ms| 68ms | -6ms | -8.080
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 836ms| 730ms | -106ms | -12.672
| | P99| 2.489s| 2.466s | -23ms | -0.924
| addTeamMember | Avg| 524ms| 526ms | 2ms | 0.382
| | P99| 992ms| 993ms | 1ms | 0.101
| autocompleteChannelsForTeamForSearch | Avg| 44ms| 47ms | 3ms | 6.856
| | P99| 493ms| 556ms | 63ms | 12.792
| autocompleteUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 200ms| 200ms | 0s | 0.000
| createCategoryForTeamForUser | Avg| 62ms| 24ms | -38ms | -60.806
| | P99| 485ms| 50ms | -435ms | -89.690
| createChannel | Avg| 982ms| 682ms | -300ms | -30.534
| | P99| 2.47s| 2.458s | -12ms | -0.486
| createDirectChannel | Avg| 1.427s| 1.434s | 7ms | 0.491
| | P99| 4.776s| 4.691s | -85ms | -1.780
| createGroupChannel | Avg| 2.205s| 2.151s | -54ms | -2.448
| | P99| 8.425s| 4.937s | -3.488s | -41.400
| createPost | Avg| 155ms| 153ms | -2ms | -1.292
| | P99| 907ms| 902ms | -5ms | -0.551
| createSchedulePost | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 87ms| 82ms | -5ms | -5.736
| createUser | Avg| 152ms| 149ms | -3ms | -1.976
| | P99| 480ms| 474ms | -6ms | -1.250
| deleteDraft | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| deletePost | Avg| 33ms| 29ms | -4ms | -12.176
| | P99| 375ms| 388ms | 13ms | 3.467
| deleteScheduledPost | Avg| 6ms| 0s | -6ms | -98.541
| | P99| 10ms| 0s | -10ms | -100.503
| followThreadByUser | Avg| 13ms| 37ms | 24ms | 185.324
| | P99| 46ms| 459ms | 413ms | 902.730
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 27ms| 24ms | -3ms | -11.298
| getCategoriesForTeamForUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 164ms| 160ms | -4ms | -2.435
| getChannel | Avg| 12ms| 13ms | 1ms | 8.109
| | P99| 113ms| 170ms | 57ms | 50.665
| getChannelMember | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 200ms| 200ms | 0s | 0.000
| getChannelMembers | Avg| 5ms| 10ms | 5ms | 111.026
| | P99| 10ms| 49ms | 39ms | 397.955
| getChannelMembersForTeamForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 86ms| 84ms | -2ms | -2.326
| getChannelMembersForUser | Avg| 9ms| 8ms | -1ms | -11.638
| | P99| 50ms| 50ms | 0s | 0.000
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 47ms| 45ms | -2ms | -4.296
| getChannelUnread | Avg| 8ms| 5ms | -3ms | -39.835
| | P99| 120ms| 76ms | -44ms | -36.589
| getChannelsForTeamForUser | Avg| 9ms| 8ms | -1ms | -11.428
| | P99| 91ms| 90ms | -1ms | -1.103
| getChannelsForUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 147ms| 130ms | -17ms | -11.603
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 53ms| 49ms | -4ms | -7.592
| getConfig | Avg| 28ms| 29ms | 1ms | 3.532
| | P99| 171ms| 145ms | -26ms | -15.191
| getDrafts | Avg| 7ms| 8ms | 1ms | 13.414
| | P99| 96ms| 95ms | -1ms | -1.046
| getFilePreview | Avg| 52ms| 51ms | -1ms | -1.907
| | P99| 228ms| 223ms | -5ms | -2.196
| getFileThumbnail | Avg| 49ms| 48ms | -1ms | -2.023
| | P99| 218ms| 214ms | -4ms | -1.833
| getPostThread | Avg| 40ms| 39ms | -1ms | -2.470
| | P99| 698ms| 703ms | 5ms | 0.716
| getPostsForChannel | Avg| 41ms| 40ms | -1ms | -2.446
| | P99| 462ms| 457ms | -5ms | -1.082
| getPostsForChannelAroundLastUnread | Avg| 134ms| 142ms | 8ms | 5.983
| | P99| 6.058s| 6.464s | 406ms | 6.702
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 41ms| 39ms | -2ms | -4.843
| getProfileImage | Avg| 43ms| 20ms | -23ms | -53.443
| | P99| 314ms| 140ms | -174ms | -55.470
| getPublicChannelsForTeam | Avg| 48ms| 47ms | -1ms | -2.085
| | P99| 211ms| 196ms | -15ms | -7.095
| getTeamMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 70ms| 65ms | -5ms | -7.161
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.668
| getTeamStats | Avg| 37ms| 42ms | 5ms | 13.441
| | P99| 93ms| 98ms | 5ms | 5.376
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.379
| getTeamsUnreadForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 62ms| 56ms | -6ms | -9.712
| getThreadsForUser | Avg| 8ms| 7ms | -1ms | -13.213
| | P99| 87ms| 85ms | -2ms | -2.302
| getUser | Avg| 4ms| 3ms | -1ms | -27.519
| | P99| 46ms| 43ms | -3ms | -6.552
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getUsers | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 160ms| 163ms | 3ms | 1.874
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.714
| getUsersByNames | Avg| 6ms| 5ms | -1ms | -18.021
| | P99| 78ms| 77ms | -1ms | -1.281
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 121ms| 122ms | 1ms | 0.825
| | P99| 434ms| 440ms | 6ms | 1.384
| logout | Avg| 62ms| 70ms | 8ms | 12.801
| | P99| 450ms| 454ms | 4ms | 0.889
| patchPost | Avg| 46ms| 31ms | -15ms | -32.803
| | P99| 416ms| 285ms | -131ms | -31.524
| removeUserCustomStatus | Avg| 871ms| 786ms | -85ms | -9.762
| | P99| 2.461s| 2.481s | 20ms | 0.813
| root | Avg| 1ms| 2ms | 1ms | 70.286
| | P99| 17ms| 23ms | 6ms | 34.884
| saveReaction | Avg| 36ms| 35ms | -1ms | -2.775
| | P99| 231ms| 227ms | -4ms | -1.735
| searchAllChannels | Avg| 413ms| 416ms | 3ms | 0.727
| | P99| 990ms| 991ms | 1ms | 0.101
| searchGroupChannels | Avg| 11ms| 12ms | 1ms | 9.115
| | P99| 87ms| 97ms | 10ms | 11.436
| searchPostsInAllTeams | Avg| 1.104s| 838ms | -266ms | -24.091
| | P99| 10s| 10s | 0s | 0.000
| searchPostsInTeam | Avg| 422ms| 410ms | -12ms | -2.845
| | P99| 8.609s| 8.464s | -145ms | -1.684
| searchUsers | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 134ms| 132ms | -2ms | -1.493
| setPostReminder | Avg| 42ms| 52ms | 10ms | 23.818
| | P99| 375ms| 415ms | 40ms | 10.667
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 24ms| 23ms | -1ms | -4.206
| | P99| 261ms| 274ms | 13ms | 4.976
| updateCategoriesForTeamForUser | Avg| 78ms| 91ms | 13ms | 16.610
| | P99| 435ms| 530ms | 95ms | 21.839
| updatePreferences | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 184ms| 184ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 13ms| 7ms | -6ms | -46.803
| | P99| 49ms| 24ms | -25ms | -50.891
| updateReadStateThreadByUser | Avg| 48ms| 45ms | -3ms | -6.284
| | P99| 407ms| 372ms | -35ms | -8.607
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 268.868
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 468ms| 455ms | -13ms | -2.780
| | P99| 1.198s| 997ms | -201ms | -16.775
| upsertDraft | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 105ms| 109ms | 4ms | 3.812
| viewChannel | Avg| 23ms| 22ms | -1ms | -4.292
| | P99| 249ms| 247ms | -2ms | -0.804
