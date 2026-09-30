### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | avg | 2ms | 7ms | 5ms | 301.34
| UserStore.GetProfilesInChannel | avg | 4ms | 14ms | 10ms | 245.64
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 6ms | 21ms | 15ms | 239.55
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 8ms | 4ms | 90.63
| JobStore.GetCountByStatusAndType | avg | 6ms | 10ms | 4ms | 68.13
| CommandWebhookStore.Cleanup | avg | 3ms | 5ms | 2ms | 64.70
| ChannelStore.CreateSidebarCategory | avg | 56ms | 88ms | 32ms | 56.79
| PostStore.SetPostReminder | avg | 16ms | 24ms | 8ms | 50.01
| RoleStore.ChannelHigherScopedPermissions | avg | 14ms | 20ms | 6ms | 43.73
| ProductNoticesStore.ClearOldNotices | avg | 39ms | 55ms | 16ms | 41.52
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 7ms | 9ms | 2ms | 27.85
| JobStore.UpdateStatusOptimistically | avg | 7ms | 9ms | 2ms | 26.68
| PostStore.Delete | avg | 36ms | 40ms | 4ms | 10.98
| ChannelStore.AnalyticsCountAll | avg | 29ms | 32ms | 3ms | 10.42
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesInChannel | p99 | 24ms | 214ms | 190ms | 806.79
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 25ms | 20ms | 403.83
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 24ms | 95ms | 71ms | 295.06
| JobStore.GetCountByStatusAndType | p99 | 50ms | 151ms | 101ms | 203.63
| JobStore.UpdateStatus | p99 | 37ms | 93ms | 56ms | 152.39
| CommandWebhookStore.Cleanup | p99 | 10ms | 24ms | 14ms | 142.85
| PostPersistentNotificationStore.DeleteExpired | p99 | 36ms | 86ms | 50ms | 137.92
| TeamStore.GetActiveMemberCount | p99 | 99ms | 223ms | 124ms | 125.25
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 99ms | 49ms | 98.49
| ChannelStore.CreateSidebarCategory | p99 | 243ms | 480ms | 237ms | 97.73
| PostPersistentNotificationStore.Get | p99 | 36ms | 71ms | 35ms | 96.55
| UserStore.GetMany | p99 | 50ms | 95ms | 45ms | 89.13
| PostStore.SetPostReminder | p99 | 222ms | 398ms | 176ms | 79.46
| BotStore.Get | p99 | 46ms | 82ms | 36ms | 78.47
| PostStore.GetPostReminders | p99 | 24ms | 41ms | 17ms | 70.80
| SessionStore.Remove | p99 | 45ms | 76ms | 31ms | 69.47
| JobStore.UpdateOptimistically | p99 | 49ms | 80ms | 31ms | 63.27
| PostStore.GetPostReminderMetadata | p99 | 81ms | 132ms | 51ms | 62.96
| RoleStore.GetByNames | p99 | 77ms | 105ms | 28ms | 36.37
| JobStore.UpdateStatusOptimistically | p99 | 73ms | 96ms | 23ms | 31.29
| UserStore.Update | p99 | 157ms | 202ms | 45ms | 28.66
| JobStore.GetNewestJobByStatusesAndType | p99 | 49ms | 63ms | 14ms | 28.46
| ScheduledPostStore.CreateScheduledPost | p99 | 63ms | 79ms | 16ms | 25.60
| ChannelStore.GetSidebarCategory | p99 | 151ms | 178ms | 27ms | 17.88
| ChannelStore.GetMany | p99 | 134ms | 157ms | 23ms | 17.10
| SessionStore.Get | p99 | 112ms | 125ms | 13ms | 11.62
| JobStore.Save | p99 | 43ms | 48ms | 5ms | 11.54
| DraftStore.Delete | p99 | 79ms | 88ms | 9ms | 11.42
| FileInfoStore.GetForPost | p99 | 73ms | 80ms | 7ms | 9.63
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 83ms | 91ms | 8ms | 9.58
| UserStore.GetUnreadCount | p99 | 74ms | 81ms | 7ms | 9.45
| UserStore.GetProfilesNotInChannel | p99 | 44ms | 48ms | 4ms | 9.20
| ChannelStore.GetChannelUnread | p99 | 92ms | 100ms | 8ms | 8.70
| ReactionStore.GetForPost | p99 | 71ms | 77ms | 6ms | 8.40
| StatusStore.SaveOrUpdateMany | p99 | 183ms | 196ms | 13ms | 7.09
| AuditStore.Save | p99 | 57ms | 61ms | 4ms | 7.07
| RoleStore.ChannelHigherScopedPermissions | p99 | 90ms | 96ms | 6ms | 6.70
| ThreadStore.GetTotalUnreadThreads | p99 | 63ms | 67ms | 4ms | 6.31
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 50ms | 53ms | 3ms | 6.04
| ThreadStore.GetThreadForUser | p99 | 122ms | 129ms | 7ms | 5.74
| FileInfoStore.Save | p99 | 90ms | 95ms | 5ms | 5.53
| ChannelStore.GetChannelsByUser | p99 | 56ms | 59ms | 3ms | 5.37
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 77ms | 81ms | 4ms | 5.17
| UserStore.GetAllProfiles | p99 | 43ms | 45ms | 2ms | 4.60
| ChannelStore.CreateDirectChannel | p99 | 447ms | 463ms | 16ms | 3.58
| PostAcknowledgementStore.GetForPost | p99 | 61ms | 63ms | 2ms | 3.26
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 94ms | 97ms | 3ms | 3.18
| ThreadStore.GetTotalThreads | p99 | 64ms | 66ms | 2ms | 3.10
| TeamStore.Get | p99 | 65ms | 67ms | 2ms | 3.07
| TeamStore.GetTotalMemberCount | p99 | 230ms | 237ms | 7ms | 3.04
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 66ms | 68ms | 2ms | 3.02
| ThreadStore.GetTotalUnreadMentions | p99 | 71ms | 73ms | 2ms | 2.82
| PostStore.Delete | p99 | 228ms | 234ms | 6ms | 2.63
| UserStore.Get | p99 | 79ms | 81ms | 2ms | 2.53
| ChannelStore.SaveMember | p99 | 316ms | 323ms | 7ms | 2.22
| JobStore.GetAllByStatus | p99 | 93ms | 95ms | 2ms | 2.16
| DraftStore.GetDraftsForUser | p99 | 93ms | 95ms | 2ms | 2.14
| ChannelStore.CreateInitialSidebarCategories | p99 | 213ms | 217ms | 4ms | 1.88
| ThreadStore.MaintainMembership | p99 | 163ms | 166ms | 3ms | 1.84
| PostStore.Get | p99 | 195ms | 198ms | 3ms | 1.54
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PropertyValueStore.SearchPropertyValues | avg | 3ms | 0s | -3ms | -107.97
| ChannelBookmarkStore.Get | avg | 6ms | 0s | -6ms | -102.76
| ChannelBookmarkStore.UpdateSortOrder | avg | 4ms | 0s | -4ms | -101.55
| ChannelBookmarkStore.Save | avg | 21ms | 0s | -21ms | -100.37
| ChannelBookmarkStore.Delete | avg | 23ms | 0s | -23ms | -99.95
| EmojiStore.Search | avg | 18ms | 0s | -18ms | -98.57
| ChannelStore.GetMemberCountsByGroup | avg | 9ms | 0s | -9ms | -94.84
| EmojiStore.GetMultipleByName | avg | 18ms | 6ms | -12ms | -66.83
| TokenStore.Cleanup | avg | 7ms | 2ms | -5ms | -66.72
| PropertyGroupStore.Get | avg | 22ms | 9ms | -13ms | -59.95
| ThreadStore.MarkAllAsReadByTeam | avg | 14ms | 6ms | -8ms | -57.79
| PreferenceStore.DeleteCategoryAndName | avg | 11ms | 5ms | -6ms | -56.77
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 9ms | 4ms | -5ms | -54.58
| SessionStore.GetSessionsExpired | avg | 12ms | 6ms | -6ms | -50.01
| PropertyFieldStore.SearchPropertyFields | avg | 16ms | 9ms | -7ms | -45.04
| ChannelStore.GetMembers | avg | 16ms | 9ms | -7ms | -43.59
| JobStore.GetAllByTypePage | avg | 18ms | 11ms | -7ms | -39.53
| PostStore.AnalyticsPostCount | avg | 321ms | 235ms | -86ms | -26.83
| ChannelStore.Save | avg | 35ms | 26ms | -9ms | -26.08
| PostStore.GetPostReminderMetadata | avg | 14ms | 11ms | -3ms | -21.20
| UserAccessTokenStore.GetByToken | avg | 9ms | 7ms | -2ms | -21.19
| RoleStore.GetByNames | avg | 10ms | 8ms | -2ms | -20.54
| ChannelStore.AutocompleteInTeamForSearch | avg | 84ms | 67ms | -17ms | -20.13
| UserStore.AnalyticsActiveCount | avg | 30ms | 25ms | -5ms | -16.91
| ChannelStore.GetTeamChannels | avg | 47ms | 40ms | -7ms | -15.03
| ChannelStore.UpdateSidebarCategories | avg | 61ms | 52ms | -9ms | -14.66
| FileInfoStore.SetContent | avg | 16ms | 14ms | -2ms | -12.59
| PostStore.Update | avg | 23ms | 21ms | -2ms | -8.58
| PostStore.SearchPostsForUser | avg | 282ms | 267ms | -15ms | -5.32
| UserStore.AutocompleteUsersInChannel | avg | 60ms | 57ms | -3ms | -5.02
| ProductNoticesStore.View | avg | 67ms | 65ms | -2ms | -3.00
| UserStore.GetAllProfilesInChannel | avg | 293ms | 288ms | -5ms | -1.71
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PropertyValueStore.SearchPropertyValues | p99 | 5ms | 0s | -5ms | -100.98
| ChannelBookmarkStore.UpdateSortOrder | p99 | 5ms | 0s | -5ms | -100.97
| ChannelStore.GetMemberCountsByGroup | p99 | 48ms | 0s | -48ms | -100.84
| EmojiStore.Search | p99 | 25ms | 0s | -25ms | -100.60
| ChannelBookmarkStore.Save | p99 | 96ms | 0s | -96ms | -100.00
| ChannelBookmarkStore.Delete | p99 | 239ms | 0s | -239ms | -99.79
| ChannelBookmarkStore.Get | p99 | 45ms | 0s | -45ms | -99.45
| ThreadStore.MarkAllAsReadByTeam | p99 | 233ms | 24ms | -209ms | -89.51
| TokenStore.Cleanup | p99 | 25ms | 5ms | -20ms | -80.97
| ChannelStore.GetMembers | p99 | 96ms | 25ms | -71ms | -73.96
| SessionStore.GetSessionsExpired | p99 | 93ms | 24ms | -69ms | -73.80
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 83ms | 22ms | -61ms | -73.05
| PreferenceStore.DeleteCategoryAndName | p99 | 86ms | 24ms | -62ms | -72.51
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 81ms | 25ms | -56ms | -69.19
| PropertyGroupStore.Get | p99 | 226ms | 80ms | -146ms | -64.60
| JobStore.GetAllByTypePage | p99 | 235ms | 91ms | -144ms | -61.28
| EmojiStore.GetMultipleByName | p99 | 97ms | 47ms | -50ms | -51.55
| PluginStore.List | p99 | 148ms | 82ms | -66ms | -44.59
| ChannelStore.Save | p99 | 365ms | 232ms | -133ms | -36.44
| PostStore.Update | p99 | 202ms | 136ms | -66ms | -32.74
| ChannelStore.UpdateSidebarCategories | p99 | 417ms | 320ms | -97ms | -23.23
| ChannelStore.GetMemberForPost | p99 | 151ms | 121ms | -30ms | -19.84
| ThreadStore.Get | p99 | 56ms | 48ms | -8ms | -14.35
| PostPersistentNotificationStore.GetSingle | p99 | 60ms | 52ms | -8ms | -13.29
| ChannelStore.GetPinnedPostCount | p99 | 85ms | 74ms | -11ms | -12.98
| UserStore.IsEmpty | p99 | 27ms | 24ms | -3ms | -11.05
| ChannelStore.GetMemberCount | p99 | 112ms | 100ms | -12ms | -10.68
| ThreadStore.UpdateMembership | p99 | 68ms | 61ms | -7ms | -10.28
| PropertyFieldStore.SearchPropertyFields | p99 | 210ms | 190ms | -20ms | -9.55
| ChannelStore.GetMemberLastViewedAt | p99 | 55ms | 50ms | -5ms | -9.11
| UserAccessTokenStore.GetByToken | p99 | 79ms | 72ms | -7ms | -8.92
| PostStore.GetPostIdAfterTime | p99 | 90ms | 82ms | -8ms | -8.85
| UserStore.GetForLogin | p99 | 59ms | 54ms | -5ms | -8.49
| LinkMetadataStore.Save | p99 | 84ms | 77ms | -7ms | -8.37
| UserStore.GetByUsername | p99 | 100ms | 92ms | -8ms | -8.01
| ThreadStore.MarkAsRead | p99 | 63ms | 58ms | -5ms | -7.96
| StatusStore.UpdateExpiredDNDStatuses | p99 | 94ms | 87ms | -7ms | -7.44
| FileInfoStore.SetContent | p99 | 149ms | 138ms | -11ms | -7.40
| PostStore.GetPostsSince | p99 | 152ms | 141ms | -11ms | -7.23
| ThreadStore.MarkAllAsReadByChannels | p99 | 81ms | 76ms | -5ms | -6.15
| ClusterDiscoveryStore.SetLastPingAt | p99 | 98ms | 92ms | -6ms | -6.14
| ChannelStore.GetTeamChannels | p99 | 237ms | 223ms | -14ms | -5.91
| FileInfoStore.GetByIds | p99 | 79ms | 75ms | -4ms | -5.09
| FileInfoStore.AttachToPost | p99 | 140ms | 133ms | -7ms | -5.01
| ChannelStore.Autocomplete | p99 | 231ms | 221ms | -10ms | -4.32
| EmojiStore.GetByName | p99 | 80ms | 77ms | -3ms | -3.77
| SessionStore.UpdateLastActivityAt | p99 | 61ms | 59ms | -2ms | -3.28
| TeamStore.SaveMember | p99 | 214ms | 207ms | -7ms | -3.27
| UserStore.Search | p99 | 199ms | 193ms | -6ms | -3.02
| ThreadStore.GetThreadUnreadReplyCount | p99 | 91ms | 89ms | -2ms | -2.20
| PostPriorityStore.GetForPosts | p99 | 110ms | 108ms | -2ms | -1.82
| ProductNoticesStore.View | p99 | 477ms | 471ms | -6ms | -1.26
| UserStore.AutocompleteUsersInChannel | p99 | 243ms | 240ms | -3ms | -1.23
| PreferenceStore.Save | p99 | 198ms | 196ms | -2ms | -1.01
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listChannelBookmarksForChannel | avg | 8ms | 31ms | 23ms | 288.51
| getServerLimits | avg | 15ms | 34ms | 19ms | 123.60
| createCategoryForTeamForUser | avg | 72ms | 103ms | 31ms | 43.28
| setPostReminder | avg | 72ms | 84ms | 12ms | 16.56
| followThreadByUser | avg | 28ms | 32ms | 4ms | 14.07
| getChannel | avg | 17ms | 19ms | 2ms | 11.85
| deletePost | avg | 55ms | 60ms | 5ms | 9.11
| getPublicChannelsForTeam | avg | 23ms | 25ms | 2ms | 8.72
| uploadFileStream | avg | 491ms | 509ms | 18ms | 3.67
| createChannel | avg | 439ms | 448ms | 9ms | 2.05
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 25ms | 97ms | 72ms | 289.65
| createCategoryForTeamForUser | p99 | 246ms | 480ms | 234ms | 95.03
| logout | p99 | 392ms | 760ms | 368ms | 93.76
| setPostReminder | p99 | 453ms | 795ms | 342ms | 75.58
| getChannelUnread | p99 | 97ms | 152ms | 55ms | 56.57
| updateUserCustomStatus | p99 | 5ms | 7ms | 2ms | 40.40
| getUsers | p99 | 116ms | 135ms | 19ms | 16.41
| getCategoriesForTeamForUser | p99 | 98ms | 110ms | 12ms | 12.25
| getChannelsForUser | p99 | 58ms | 63ms | 5ms | 8.69
| getTeamsForUser | p99 | 57ms | 61ms | 4ms | 7.06
| upsertDraft | p99 | 99ms | 105ms | 6ms | 6.06
| getClientConfig | p99 | 164ms | 173ms | 9ms | 5.50
| uploadFileStream | p99 | 1.827s | 1.927s | 100ms | 5.47
| getPostsForChannelAroundLastUnread | p99 | 252ms | 264ms | 12ms | 4.77
| getChannelMember | p99 | 154ms | 160ms | 6ms | 3.91
| getAllTeams | p99 | 78ms | 81ms | 3ms | 3.86
| getChannelMembersForUser | p99 | 61ms | 63ms | 2ms | 3.27
| getTeamStats | p99 | 230ms | 237ms | 7ms | 3.04
| getTeamsUnreadForUser | p99 | 135ms | 139ms | 4ms | 2.96
| getPreferences | p99 | 72ms | 74ms | 2ms | 2.77
| createChannel | p99 | 2.305s | 2.365s | 60ms | 2.60
| getUser | p99 | 143ms | 146ms | 3ms | 2.10
| getTeamScheduledPosts | p99 | 97ms | 99ms | 2ms | 2.07
| getDrafts | p99 | 97ms | 99ms | 2ms | 2.07
| getProfileImage | p99 | 446ms | 455ms | 9ms | 2.02
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 10ms | 0s | -10ms | -101.61
| deleteChannelBookmark | avg | 13ms | 0s | -13ms | -101.24
| updateChannelBookmark | avg | 58ms | 0s | -58ms | -99.25
| createChannelBookmark | avg | 36ms | 0s | -36ms | -98.84
| createEmoji | avg | 16ms | 0s | -16ms | -98.27
| autocompleteEmojis | avg | 18ms | 0s | -18ms | -98.23
| getSystemPropertyValues | avg | 5ms | 0s | -5ms | -95.61
| listCPAFields | avg | 117ms | 10ms | -107ms | -91.49
| getRolesByNames | avg | 7ms | 1ms | -6ms | -87.70
| updateReadStateAllThreadsByUser | avg | 14ms | 6ms | -8ms | -57.39
| getJobsByType | avg | 25ms | 12ms | -13ms | -51.83
| getFilteredUsersStats | avg | 25ms | 14ms | -11ms | -44.09
| getChannelMembers | avg | 18ms | 11ms | -7ms | -38.80
| getPropertyFields | avg | 42ms | 26ms | -16ms | -38.53
| root | avg | 8ms | 6ms | -2ms | -26.47
| autocompleteChannelsForTeamForSearch | avg | 85ms | 67ms | -18ms | -21.19
| handleCheckCWSConnection | avg | 58ms | 46ms | -12ms | -20.73
| searchPostsInAllTeams | avg | 380ms | 337ms | -43ms | -11.32
| updateCategoriesForTeamForUser | avg | 102ms | 91ms | -11ms | -10.75
| createGroupChannel | avg | 689ms | 625ms | -64ms | -9.28
| removeUserCustomStatus | avg | 273ms | 254ms | -19ms | -6.96
| patchPost | avg | 72ms | 67ms | -5ms | -6.90
| createDirectChannel | avg | 430ms | 401ms | -29ms | -6.74
| logout | avg | 91ms | 85ms | -6ms | -6.58
| addChannelMember | avg | 387ms | 369ms | -18ms | -4.66
| updateReadStateThreadByUser | avg | 99ms | 95ms | -4ms | -4.05
| autocompleteUsers | avg | 55ms | 53ms | -2ms | -3.61
| addTeamMember | avg | 1.001s | 970ms | -31ms | -3.10
| createPost | avg | 506ms | 495ms | -11ms | -2.17
| createUser | avg | 301ms | 295ms | -6ms | -1.99
| searchPostsInTeam | avg | 266ms | 263ms | -3ms | -1.13
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -101.18
| createEmoji | p99 | 25ms | 0s | -25ms | -100.60
| autocompleteEmojis | p99 | 25ms | 0s | -25ms | -100.60
| getSystemPropertyValues | p99 | 10ms | 0s | -10ms | -100.46
| channelMemberCountsByGroup | p99 | 48ms | 0s | -48ms | -100.42
| updateChannelBookmark | p99 | 485ms | 0s | -485ms | -100.00
| createChannelBookmark | p99 | 98ms | 0s | -98ms | -99.49
| listCPAFields | p99 | 493ms | 25ms | -468ms | -95.02
| updateReadStateAllThreadsByUser | p99 | 233ms | 24ms | -209ms | -89.51
| getRolesByNames | p99 | 49ms | 10ms | -39ms | -79.59
| getChannelMembers | p99 | 96ms | 25ms | -71ms | -73.96
| getJobsByType | p99 | 238ms | 91ms | -147ms | -61.77
| handleCheckCWSConnection | p99 | 100ms | 50ms | -50ms | -50.25
| getPropertyFields | p99 | 470ms | 237ms | -233ms | -49.57
| listChannelBookmarksForChannel | p99 | 88ms | 50ms | -38ms | -43.29
| deletePost | p99 | 427ms | 242ms | -185ms | -43.28
| root | p99 | 135ms | 91ms | -44ms | -32.57
| unfollowThreadByUser | p99 | 358ms | 248ms | -110ms | -30.72
| createGroupChannel | p99 | 2.983s | 2.404s | -579ms | -19.41
| searchPostsInAllTeams | p99 | 3.062s | 2.677s | -385ms | -12.57
| getPostThread | p99 | 341ms | 303ms | -38ms | -11.14
| getUserStatusesByIds | p99 | 42ms | 38ms | -4ms | -9.50
| patchPost | p99 | 462ms | 430ms | -32ms | -6.93
| createDirectChannel | p99 | 2.2s | 2.062s | -138ms | -6.27
| getChannel | p99 | 151ms | 144ms | -7ms | -4.62
| updateCategoriesForTeamForUser | p99 | 670ms | 640ms | -30ms | -4.48
| searchAllChannels | p99 | 235ms | 226ms | -9ms | -3.83
| addChannelMember | p99 | 2.149s | 2.071s | -78ms | -3.63
| searchUsers | p99 | 206ms | 201ms | -5ms | -2.43
| removeUserCustomStatus | p99 | 962ms | 939ms | -23ms | -2.39
| createSchedulePost | p99 | 88ms | 86ms | -2ms | -2.29
| getChannelStats | p99 | 88ms | 86ms | -2ms | -2.26
| updateReadStateThreadByUser | p99 | 490ms | 479ms | -11ms | -2.24
| autocompleteChannelsForTeamForSearch | p99 | 248ms | 244ms | -4ms | -1.62
| addTeamMember | p99 | 4.54s | 4.482s | -58ms | -1.28
| autocompleteUsers | p99 | 242ms | 239ms | -3ms | -1.24
| getPostsForChannel | p99 | 927ms | 916ms | -11ms | -1.19
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 57ms| 61ms | 4ms | 7.071
| BotStore.Get |  Avg| 7ms| 8ms | 1ms | 13.721
| |  P99| 46ms| 82ms | 36ms | 78.474
| ChannelBookmarkStore.Delete |  Avg| 23ms| 0s | -23ms | -99.946
| |  P99| 239ms| 0s | -239ms | -99.793
| ChannelBookmarkStore.Get |  Avg| 6ms| 0s | -6ms | -102.762
| |  P99| 45ms| 0s | -45ms | -99.453
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 7ms| 9ms | 2ms | 27.851
| |  P99| 81ms| 25ms | -56ms | -69.190
| ChannelBookmarkStore.Save |  Avg| 21ms| 0s | -21ms | -100.374
| |  P99| 96ms| 0s | -96ms | -100.001
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 4ms| 0s | -4ms | -101.551
| |  P99| 5ms| 0s | -5ms | -100.967
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 29ms| 32ms | 3ms | 10.423
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 46ms| 45ms | -1ms | -2.170
| |  P99| 231ms| 221ms | -10ms | -4.323
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 84ms| 67ms | -17ms | -20.126
| |  P99| 243ms| 244ms | 1ms | 0.412
| ChannelStore.CreateDirectChannel |  Avg| 62ms| 63ms | 1ms | 1.625
| |  P99| 447ms| 463ms | 16ms | 3.580
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 23ms | 1ms | 4.470
| |  P99| 213ms| 217ms | 4ms | 1.882
| ChannelStore.CreateSidebarCategory |  Avg| 56ms| 88ms | 32ms | 56.791
| |  P99| 243ms| 480ms | 237ms | 97.731
| ChannelStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 96ms | 1ms | 1.055
| ChannelStore.GetAllChannelMembersForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 198ms| 198ms | 0s | 0.000
| ChannelStore.GetBoardChannel |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 87ms | 1ms | 1.159
| ChannelStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 77ms| 78ms | 1ms | 1.292
| ChannelStore.GetChannelUnread |  Avg| 9ms| 10ms | 1ms | 11.088
| |  P99| 92ms| 100ms | 8ms | 8.701
| ChannelStore.GetChannels |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.111
| ChannelStore.GetChannelsByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 56ms| 59ms | 3ms | 5.374
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.359
| ChannelStore.GetFileCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 84ms| 84ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 76ms| 76ms | 0s | 0.000
| ChannelStore.GetMany |  Avg| 16ms| 15ms | -1ms | -6.386
| |  P99| 134ms| 157ms | 23ms | 17.103
| ChannelStore.GetMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 71ms | 1ms | 1.421
| ChannelStore.GetMemberCount |  Avg| 27ms| 26ms | -1ms | -3.681
| |  P99| 112ms| 100ms | -12ms | -10.679
| ChannelStore.GetMemberCountsByGroup |  Avg| 9ms| 0s | -9ms | -94.838
| |  P99| 48ms| 0s | -48ms | -100.841
| ChannelStore.GetMemberForPost |  Avg| 32ms| 31ms | -1ms | -3.150
| |  P99| 151ms| 121ms | -30ms | -19.845
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 55ms| 50ms | -5ms | -9.113
| ChannelStore.GetMembers |  Avg| 16ms| 9ms | -7ms | -43.594
| |  P99| 96ms| 25ms | -71ms | -73.959
| ChannelStore.GetMembersForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 87ms| 88ms | 1ms | 1.143
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 6ms| 21ms | 15ms | 239.553
| |  P99| 24ms| 95ms | 71ms | 295.064
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 6ms | -1ms | -15.310
| |  P99| 59ms| 58ms | -1ms | -1.703
| ChannelStore.GetPinnedPostCount |  Avg| 8ms| 7ms | -1ms | -12.879
| |  P99| 85ms| 74ms | -11ms | -12.975
| ChannelStore.GetPublicChannelsForTeam |  Avg| 22ms| 23ms | 1ms | 4.608
| |  P99| 97ms| 98ms | 1ms | 1.032
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 94ms| 97ms | 3ms | 3.178
| ChannelStore.GetSidebarCategory |  Avg| 17ms| 16ms | -1ms | -5.934
| |  P99| 151ms| 178ms | 27ms | 17.880
| ChannelStore.GetTeamChannels |  Avg| 47ms| 40ms | -7ms | -15.034
| |  P99| 237ms| 223ms | -14ms | -5.907
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 74ms| 74ms | 0s | 0.000
| ChannelStore.Save |  Avg| 35ms| 26ms | -9ms | -26.077
| |  P99| 365ms| 232ms | -133ms | -36.438
| ChannelStore.SaveMember |  Avg| 48ms| 47ms | -1ms | -2.089
| |  P99| 316ms| 323ms | 7ms | 2.216
| ChannelStore.SearchGroupChannels |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 93ms| 94ms | 1ms | 1.073
| ChannelStore.UpdateLastViewedAt |  Avg| 8ms| 7ms | -1ms | -13.202
| |  P99| 68ms| 68ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 61ms| 52ms | -9ms | -14.659
| |  P99| 417ms| 320ms | -97ms | -23.234
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 70ms| 71ms | 1ms | 1.430
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 92ms | -6ms | -6.143
| CommandWebhookStore.Cleanup |  Avg| 3ms| 5ms | 2ms | 64.696
| |  P99| 10ms| 24ms | 14ms | 142.855
| DraftStore.Delete |  Avg| 8ms| 9ms | 1ms | 12.527
| |  P99| 79ms| 88ms | 9ms | 11.422
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 12ms | -1ms | -7.447
| |  P99| 48ms| 48ms | 0s | 0.000
| DraftStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 94ms| 93ms | -1ms | -1.064
| DraftStore.GetDraftsForUser |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 95ms | 2ms | 2.143
| DraftStore.Upsert |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 77ms | -3ms | -3.770
| EmojiStore.GetMultipleByName |  Avg| 18ms| 6ms | -12ms | -66.831
| |  P99| 97ms| 47ms | -50ms | -51.546
| EmojiStore.Search |  Avg| 18ms| 0s | -18ms | -98.571
| |  P99| 25ms| 0s | -25ms | -100.604
| FileInfoStore.AttachToPost |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 140ms| 133ms | -7ms | -5.012
| FileInfoStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.111
| FileInfoStore.GetByIds |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 75ms | -4ms | -5.091
| FileInfoStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 80ms | 7ms | 9.634
| FileInfoStore.Save |  Avg| 10ms| 11ms | 1ms | 9.614
| |  P99| 90ms| 95ms | 5ms | 5.529
| FileInfoStore.SetContent |  Avg| 16ms| 14ms | -2ms | -12.594
| |  P99| 149ms| 138ms | -11ms | -7.398
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 5ms | 1ms | 22.263
| |  P99| 46ms| 47ms | 1ms | 2.175
| GroupStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.040
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 73ms| 74ms | 1ms | 1.364
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 4ms | 1ms | 37.159
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 10ms| 9ms | -1ms | -9.997
| |  P99| 93ms| 95ms | 2ms | 2.156
| JobStore.GetAllByTypePage |  Avg| 18ms| 11ms | -7ms | -39.532
| |  P99| 235ms| 91ms | -144ms | -61.275
| JobStore.GetCountByStatusAndType |  Avg| 6ms| 10ms | 4ms | 68.131
| |  P99| 50ms| 151ms | 101ms | 203.629
| JobStore.GetNewestJobByStatusesAndType |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 63ms | 14ms | 28.455
| JobStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 43ms| 48ms | 5ms | 11.544
| JobStore.UpdateOptimistically |  Avg| 8ms| 9ms | 1ms | 12.726
| |  P99| 49ms| 80ms | 31ms | 63.267
| JobStore.UpdateStatus |  Avg| 7ms| 8ms | 1ms | 14.354
| |  P99| 37ms| 93ms | 56ms | 152.386
| JobStore.UpdateStatusOptimistically |  Avg| 7ms| 9ms | 2ms | 26.682
| |  P99| 73ms| 96ms | 23ms | 31.294
| LinkMetadataStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 74ms| 74ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 8ms| 7ms | -1ms | -12.554
| |  P99| 84ms| 77ms | -7ms | -8.369
| PluginStore.List |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 148ms| 82ms | -66ms | -44.587
| PostAcknowledgementStore.GetForPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 61ms| 63ms | 2ms | 3.260
| PostAcknowledgementStore.GetForPosts |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 8ms | 4ms | 90.630
| |  P99| 36ms| 86ms | 50ms | 137.924
| PostPersistentNotificationStore.Get |  Avg| 6ms| 7ms | 1ms | 16.849
| |  P99| 36ms| 71ms | 35ms | 96.555
| PostPersistentNotificationStore.GetSingle |  Avg| 6ms| 5ms | -1ms | -17.679
| |  P99| 60ms| 52ms | -8ms | -13.293
| PostPriorityStore.GetForPostWithContext |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 63ms| 64ms | 1ms | 1.588
| PostPriorityStore.GetForPosts |  Avg| 11ms| 10ms | -1ms | -9.435
| |  P99| 110ms| 108ms | -2ms | -1.817
| PostStore.AnalyticsPostCount |  Avg| 321ms| 235ms | -86ms | -26.832
| |  P99| 498ms| 496ms | -2ms | -0.402
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 36ms| 40ms | 4ms | 10.982
| |  P99| 228ms| 234ms | 6ms | 2.629
| PostStore.Get |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 195ms| 198ms | 3ms | 1.540
| PostStore.GetEtag |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 8ms| 7ms | -1ms | -12.109
| |  P99| 90ms| 82ms | -8ms | -8.855
| PostStore.GetPostReminderMetadata |  Avg| 14ms| 11ms | -3ms | -21.201
| |  P99| 81ms| 132ms | 51ms | 62.964
| PostStore.GetPostReminders |  Avg| 6ms| 5ms | -1ms | -17.082
| |  P99| 24ms| 41ms | 17ms | 70.804
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.056
| PostStore.GetPostsAfter |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.128
| PostStore.GetPostsBefore |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 12ms| 11ms | -1ms | -8.681
| |  P99| 80ms| 79ms | -1ms | -1.243
| PostStore.GetPostsSince |  Avg| 21ms| 20ms | -1ms | -4.779
| |  P99| 152ms| 141ms | -11ms | -7.227
| PostStore.GetSingle |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 70ms | 1ms | 1.453
| PostStore.GetVisiblePostIdAroundTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 56ms| 56ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 231ms| 232ms | 1ms | 0.433
| PostStore.SearchPostsForUser |  Avg| 282ms| 267ms | -15ms | -5.322
| |  P99| 2.459s| 2.46s | 1ms | 0.041
| PostStore.SetPostReminder |  Avg| 16ms| 24ms | 8ms | 50.008
| |  P99| 222ms| 398ms | 176ms | 79.458
| PostStore.Update |  Avg| 23ms| 21ms | -2ms | -8.581
| |  P99| 202ms| 136ms | -66ms | -32.743
| PreferenceStore.DeleteCategoryAndName |  Avg| 11ms| 5ms | -6ms | -56.766
| |  P99| 86ms| 24ms | -62ms | -72.512
| PreferenceStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 81ms | 1ms | 1.255
| PreferenceStore.GetAll |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 68ms| 69ms | 1ms | 1.465
| PreferenceStore.Save |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 198ms| 196ms | -2ms | -1.012
| ProductNoticesStore.ClearOldNotices |  Avg| 39ms| 55ms | 16ms | 41.516
| |  P99| 50ms| 99ms | 49ms | 98.492
| ProductNoticesStore.View |  Avg| 67ms| 65ms | -2ms | -2.998
| |  P99| 477ms| 471ms | -6ms | -1.257
| PropertyFieldStore.SearchPropertyFields |  Avg| 16ms| 9ms | -7ms | -45.037
| |  P99| 210ms| 190ms | -20ms | -9.546
| PropertyGroupStore.Get |  Avg| 22ms| 9ms | -13ms | -59.951
| |  P99| 226ms| 80ms | -146ms | -64.600
| PropertyValueStore.SearchPropertyValues |  Avg| 3ms| 0s | -3ms | -107.973
| |  P99| 5ms| 0s | -5ms | -100.981
| ReactionStore.GetForPost |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 71ms| 77ms | 6ms | 8.399
| RoleStore.ChannelHigherScopedPermissions |  Avg| 14ms| 20ms | 6ms | 43.727
| |  P99| 90ms| 96ms | 6ms | 6.704
| RoleStore.GetByNames |  Avg| 10ms| 8ms | -2ms | -20.540
| |  P99| 77ms| 105ms | 28ms | 36.366
| ScheduledPostStore.CreateScheduledPost |  Avg| 8ms| 9ms | 1ms | 12.228
| |  P99| 63ms| 79ms | 16ms | 25.595
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 10ms| 9ms | -1ms | -10.167
| |  P99| 83ms| 91ms | 8ms | 9.581
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 50ms| 53ms | 3ms | 6.044
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 9ms| 4ms | -5ms | -54.577
| |  P99| 83ms| 22ms | -61ms | -73.054
| SessionStore.Get |  Avg| 12ms| 11ms | -1ms | -8.686
| |  P99| 112ms| 125ms | 13ms | 11.619
| SessionStore.GetLRUSessions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.035
| SessionStore.GetSessionsExpired |  Avg| 12ms| 6ms | -6ms | -50.013
| |  P99| 93ms| 24ms | -69ms | -73.797
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 81ms | 4ms | 5.168
| SessionStore.Remove |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 76ms | 31ms | 69.468
| SessionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.100
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 61ms| 59ms | -2ms | -3.282
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 77ms| 77ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 84ms | -1ms | -1.177
| StatusStore.SaveOrUpdateMany |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 183ms| 196ms | 13ms | 7.092
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 9ms| 8ms | -1ms | -11.572
| |  P99| 94ms| 87ms | -7ms | -7.440
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 69ms| 70ms | 1ms | 1.448
| SystemStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.048
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 7ms | 5ms | 301.342
| |  P99| 5ms| 25ms | 20ms | 403.828
| TeamStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 65ms| 67ms | 2ms | 3.067
| TeamStore.GetActiveMemberCount |  Avg| 54ms| 55ms | 1ms | 1.865
| |  P99| 99ms| 223ms | 124ms | 125.253
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 61ms| 62ms | 1ms | 1.651
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 66ms| 68ms | 2ms | 3.017
| TeamStore.GetMember |  Avg| 5ms| 4ms | -1ms | -21.970
| |  P99| 47ms| 48ms | 1ms | 2.114
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 6ms | 1ms | 18.229
| |  P99| 55ms| 56ms | 1ms | 1.822
| TeamStore.GetTeamsForUser |  Avg| 6ms| 5ms | -1ms | -18.059
| |  P99| 59ms| 58ms | -1ms | -1.703
| TeamStore.GetTotalMemberCount |  Avg| 55ms| 55ms | 0s | 0.000
| |  P99| 230ms| 237ms | 7ms | 3.037
| TeamStore.SaveMember |  Avg| 33ms| 32ms | -1ms | -3.062
| |  P99| 214ms| 207ms | -7ms | -3.274
| TemporaryPostStore.GetExpiredPosts |  Avg| 7ms| 6ms | -1ms | -15.208
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.Get |  Avg| 7ms| 6ms | -1ms | -13.979
| |  P99| 56ms| 48ms | -8ms | -14.351
| ThreadStore.GetMembershipForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 81ms | -1ms | -1.213
| ThreadStore.GetTeamsUnreadForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 86ms | 1ms | 1.172
| ThreadStore.GetThreadFollowers |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 65ms| 66ms | 1ms | 1.549
| ThreadStore.GetThreadForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 122ms| 129ms | 7ms | 5.742
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 91ms| 89ms | -2ms | -2.198
| ThreadStore.GetThreadsForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 92ms| 93ms | 1ms | 1.087
| ThreadStore.GetTotalThreads |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 64ms| 66ms | 2ms | 3.102
| ThreadStore.GetTotalUnreadMentions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 71ms| 73ms | 2ms | 2.819
| ThreadStore.GetTotalUnreadThreads |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 63ms| 67ms | 4ms | 6.313
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 67ms| 68ms | 1ms | 1.491
| ThreadStore.MaintainMembership |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 163ms| 166ms | 3ms | 1.843
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 76ms | -5ms | -6.153
| ThreadStore.MarkAllAsReadByTeam |  Avg| 14ms| 6ms | -8ms | -57.791
| |  P99| 233ms| 24ms | -209ms | -89.510
| ThreadStore.MarkAsRead |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 63ms| 58ms | -5ms | -7.956
| ThreadStore.UpdateMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 61ms | -7ms | -10.275
| TokenStore.Cleanup |  Avg| 7ms| 2ms | -5ms | -66.724
| |  P99| 25ms| 5ms | -20ms | -80.972
| UserAccessTokenStore.GetByToken |  Avg| 9ms| 7ms | -2ms | -21.189
| |  P99| 79ms| 72ms | -7ms | -8.917
| UserStore.AnalyticsActiveCount |  Avg| 30ms| 25ms | -5ms | -16.911
| |  P99| 50ms| 49ms | -1ms | -2.020
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 3ms | 1ms | 48.656
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 60ms| 57ms | -3ms | -5.023
| |  P99| 243ms| 240ms | -3ms | -1.233
| UserStore.Count |  Avg| 21ms| 20ms | -1ms | -4.819
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 81ms | 2ms | 2.528
| UserStore.GetAllProfiles |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.601
| UserStore.GetAllProfilesInChannel |  Avg| 293ms| 288ms | -5ms | -1.707
| |  P99| 985ms| 986ms | 1ms | 0.102
| UserStore.GetByUsername |  Avg| 10ms| 9ms | -1ms | -10.427
| |  P99| 100ms| 92ms | -8ms | -8.010
| UserStore.GetForLogin |  Avg| 6ms| 5ms | -1ms | -17.607
| |  P99| 59ms| 54ms | -5ms | -8.487
| UserStore.GetMany |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 50ms| 95ms | 45ms | 89.130
| UserStore.GetProfileByIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.141
| UserStore.GetProfilesByUsernames |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 4ms| 14ms | 10ms | 245.637
| |  P99| 24ms| 214ms | 190ms | 806.788
| UserStore.GetProfilesNotInChannel |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 44ms| 48ms | 4ms | 9.195
| UserStore.GetUnreadCount |  Avg| 7ms| 8ms | 1ms | 13.927
| |  P99| 74ms| 81ms | 7ms | 9.454
| UserStore.IsEmpty |  Avg| 3ms| 2ms | -1ms | -38.401
| |  P99| 27ms| 24ms | -3ms | -11.051
| UserStore.Save |  Avg| 138ms| 138ms | 0s | 0.000
| |  P99| 429ms| 432ms | 3ms | 0.700
| UserStore.Search |  Avg| 41ms| 40ms | -1ms | -2.459
| |  P99| 199ms| 193ms | -6ms | -3.021
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| UserStore.Update |  Avg| 19ms| 20ms | 1ms | 5.230
| |  P99| 157ms| 202ms | 45ms | 28.656
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 66ms| 66ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.073
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 53ms| 53ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 387ms| 369ms | -18ms | -4.656
| | P99| 2.149s| 2.071s | -78ms | -3.629
| addTeamMember | Avg| 1.001s| 970ms | -31ms | -3.097
| | P99| 4.54s| 4.482s | -58ms | -1.278
| autocompleteChannelsForTeamForSearch | Avg| 85ms| 67ms | -18ms | -21.194
| | P99| 248ms| 244ms | -4ms | -1.616
| autocompleteEmojis | Avg| 18ms| 0s | -18ms | -98.231
| | P99| 25ms| 0s | -25ms | -100.604
| autocompleteUsers | Avg| 55ms| 53ms | -2ms | -3.614
| | P99| 242ms| 239ms | -3ms | -1.239
| channelMemberCountsByGroup | Avg| 10ms| 0s | -10ms | -101.606
| | P99| 48ms| 0s | -48ms | -100.420
| createCategoryForTeamForUser | Avg| 72ms| 103ms | 31ms | 43.278
| | P99| 246ms| 480ms | 234ms | 95.025
| createChannel | Avg| 439ms| 448ms | 9ms | 2.051
| | P99| 2.305s| 2.365s | 60ms | 2.603
| createChannelBookmark | Avg| 36ms| 0s | -36ms | -98.841
| | P99| 98ms| 0s | -98ms | -99.493
| createDirectChannel | Avg| 430ms| 401ms | -29ms | -6.737
| | P99| 2.2s| 2.062s | -138ms | -6.273
| createEmoji | Avg| 16ms| 0s | -16ms | -98.266
| | P99| 25ms| 0s | -25ms | -100.604
| createGroupChannel | Avg| 689ms| 625ms | -64ms | -9.283
| | P99| 2.983s| 2.404s | -579ms | -19.409
| createPost | Avg| 506ms| 495ms | -11ms | -2.173
| | P99| 2.443s| 2.439s | -4ms | -0.164
| createSchedulePost | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 88ms| 86ms | -2ms | -2.286
| createUser | Avg| 301ms| 295ms | -6ms | -1.991
| | P99| 994ms| 995ms | 1ms | 0.101
| deleteChannelBookmark | Avg| 13ms| 0s | -13ms | -101.241
| | P99| 25ms| 0s | -25ms | -101.182
| deleteDraft | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| deletePost | Avg| 55ms| 60ms | 5ms | 9.112
| | P99| 427ms| 242ms | -185ms | -43.276
| followThreadByUser | Avg| 28ms| 32ms | 4ms | 14.075
| | P99| 226ms| 224ms | -2ms | -0.885
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 78ms| 81ms | 3ms | 3.860
| getCategoriesForTeamForUser | Avg| 11ms| 12ms | 1ms | 8.788
| | P99| 98ms| 110ms | 12ms | 12.246
| getChannel | Avg| 17ms| 19ms | 2ms | 11.847
| | P99| 151ms| 144ms | -7ms | -4.623
| getChannelMember | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 154ms| 160ms | 6ms | 3.906
| getChannelMembers | Avg| 18ms| 11ms | -7ms | -38.803
| | P99| 96ms| 25ms | -71ms | -73.959
| getChannelMembersForTeamForUser | Avg| 9ms| 10ms | 1ms | 10.703
| | P99| 89ms| 90ms | 1ms | 1.124
| getChannelMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 61ms| 63ms | 2ms | 3.268
| getChannelStats | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 88ms| 86ms | -2ms | -2.261
| getChannelUnread | Avg| 10ms| 11ms | 1ms | 10.012
| | P99| 97ms| 152ms | 55ms | 56.571
| getChannelsForTeamForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 92ms| 93ms | 1ms | 1.092
| getChannelsForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 58ms| 63ms | 5ms | 8.693
| getClientConfig | Avg| 12ms| 13ms | 1ms | 8.132
| | P99| 164ms| 173ms | 9ms | 5.497
| getDrafts | Avg| 11ms| 12ms | 1ms | 8.833
| | P99| 97ms| 99ms | 2ms | 2.067
| getFilePreview | Avg| 64ms| 65ms | 1ms | 1.568
| | P99| 247ms| 248ms | 1ms | 0.404
| getFileThumbnail | Avg| 58ms| 59ms | 1ms | 1.733
| | P99| 241ms| 243ms | 2ms | 0.829
| getFilteredUsersStats | Avg| 25ms| 14ms | -11ms | -44.089
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 25ms| 12ms | -13ms | -51.830
| | P99| 238ms| 91ms | -147ms | -61.765
| getPostThread | Avg| 46ms| 45ms | -1ms | -2.194
| | P99| 341ms| 303ms | -38ms | -11.144
| getPostsForChannel | Avg| 101ms| 100ms | -1ms | -0.994
| | P99| 927ms| 916ms | -11ms | -1.187
| getPostsForChannelAroundLastUnread | Avg| 34ms| 35ms | 1ms | 2.935
| | P99| 252ms| 264ms | 12ms | 4.767
| getPreferences | Avg| 6ms| 7ms | 1ms | 15.527
| | P99| 72ms| 74ms | 2ms | 2.772
| getProfileImage | Avg| 74ms| 75ms | 1ms | 1.343
| | P99| 446ms| 455ms | 9ms | 2.019
| getPropertyFields | Avg| 42ms| 26ms | -16ms | -38.534
| | P99| 470ms| 237ms | -233ms | -49.573
| getPublicChannelsForTeam | Avg| 23ms| 25ms | 2ms | 8.716
| | P99| 97ms| 98ms | 1ms | 1.030
| getRolesByNames | Avg| 7ms| 1ms | -6ms | -87.699
| | P99| 49ms| 10ms | -39ms | -79.592
| getServerLimits | Avg| 15ms| 34ms | 19ms | 123.600
| | P99| 25ms| 97ms | 72ms | 289.647
| getSystemPropertyValues | Avg| 5ms| 0s | -5ms | -95.614
| | P99| 10ms| 0s | -10ms | -100.464
| getTeamMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 90ms| 90ms | 0s | 0.000
| getTeamMembersForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 72ms| 73ms | 1ms | 1.397
| getTeamScheduledPosts | Avg| 10ms| 11ms | 1ms | 9.647
| | P99| 97ms| 99ms | 2ms | 2.068
| getTeamStats | Avg| 61ms| 61ms | 0s | 0.000
| | P99| 230ms| 237ms | 7ms | 3.037
| getTeamsForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 57ms| 61ms | 4ms | 7.062
| getTeamsUnreadForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 135ms| 139ms | 4ms | 2.963
| getThreadsForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| getUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 143ms| 146ms | 3ms | 2.101
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 42ms| 38ms | -4ms | -9.497
| getUsers | Avg| 8ms| 9ms | 1ms | 12.156
| | P99| 116ms| 135ms | 19ms | 16.415
| getUsersByIds | Avg| 2ms| 3ms | 1ms | 40.640
| | P99| 32ms| 31ms | -1ms | -3.109
| getUsersByNames | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 93ms| 93ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 58ms| 46ms | -12ms | -20.728
| | P99| 100ms| 50ms | -50ms | -50.251
| listCPAFields | Avg| 117ms| 10ms | -107ms | -91.492
| | P99| 493ms| 25ms | -468ms | -95.024
| listChannelBookmarksForChannel | Avg| 8ms| 31ms | 23ms | 288.508
| | P99| 88ms| 50ms | -38ms | -43.290
| login | Avg| 117ms| 118ms | 1ms | 0.854
| | P99| 625ms| 631ms | 6ms | 0.960
| logout | Avg| 91ms| 85ms | -6ms | -6.576
| | P99| 392ms| 760ms | 368ms | 93.765
| patchPost | Avg| 72ms| 67ms | -5ms | -6.900
| | P99| 462ms| 430ms | -32ms | -6.928
| removeUserCustomStatus | Avg| 273ms| 254ms | -19ms | -6.961
| | P99| 962ms| 939ms | -23ms | -2.392
| root | Avg| 8ms| 6ms | -2ms | -26.467
| | P99| 135ms| 91ms | -44ms | -32.572
| saveReaction | Avg| 48ms| 48ms | 0s | 0.000
| | P99| 240ms| 240ms | 0s | 0.000
| searchAllChannels | Avg| 47ms| 46ms | -1ms | -2.134
| | P99| 235ms| 226ms | -9ms | -3.832
| searchGroupChannels | Avg| 11ms| 12ms | 1ms | 8.835
| | P99| 95ms| 95ms | 0s | 0.000
| searchPostsInAllTeams | Avg| 380ms| 337ms | -43ms | -11.320
| | P99| 3.062s| 2.677s | -385ms | -12.571
| searchPostsInTeam | Avg| 266ms| 263ms | -3ms | -1.129
| | P99| 2.441s| 2.448s | 7ms | 0.287
| searchUsers | Avg| 42ms| 42ms | 0s | 0.000
| | P99| 206ms| 201ms | -5ms | -2.430
| setPostReminder | Avg| 72ms| 84ms | 12ms | 16.559
| | P99| 453ms| 795ms | 342ms | 75.580
| submitPerformanceReport | Avg| 0s| 1ms | 1ms | 473.971
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 43ms| 42ms | -1ms | -2.311
| | P99| 358ms| 248ms | -110ms | -30.715
| updateCategoriesForTeamForUser | Avg| 102ms| 91ms | -11ms | -10.748
| | P99| 670ms| 640ms | -30ms | -4.478
| updateChannelBookmark | Avg| 58ms| 0s | -58ms | -99.251
| | P99| 485ms| 0s | -485ms | -100.001
| updatePreferences | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 239ms| 237ms | -2ms | -0.835
| updateReadStateAllThreadsByUser | Avg| 14ms| 6ms | -8ms | -57.393
| | P99| 233ms| 24ms | -209ms | -89.510
| updateReadStateThreadByUser | Avg| 99ms| 95ms | -4ms | -4.050
| | P99| 490ms| 479ms | -11ms | -2.243
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 984.528
| | P99| 5ms| 7ms | 2ms | 40.404
| uploadFileStream | Avg| 491ms| 509ms | 18ms | 3.666
| | P99| 1.827s| 1.927s | 100ms | 5.472
| upsertDraft | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 99ms| 105ms | 6ms | 6.064
| viewChannel | Avg| 41ms| 41ms | 0s | 0.000
| | P99| 364ms| 365ms | 1ms | 0.275
