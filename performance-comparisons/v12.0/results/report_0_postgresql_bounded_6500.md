### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Get | avg | 3ms | 5ms | 2ms | 79.90
| StatusStore.SaveOrUpdateMany | avg | 6ms | 8ms | 2ms | 31.33
| ChannelStore.AutocompleteInTeamForSearch | avg | 45ms | 55ms | 10ms | 22.01
| PostStore.SearchPostsForUser | avg | 125ms | 152ms | 27ms | 21.55
| ChannelStore.GetTeamChannels | avg | 25ms | 27ms | 2ms | 7.91
| ProductNoticesStore.View | avg | 35ms | 37ms | 2ms | 5.70
| UserStore.Save | avg | 120ms | 124ms | 4ms | 3.34
| UserStore.GetAllProfilesInChannel | avg | 152ms | 156ms | 4ms | 2.63
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Get | p99 | 5ms | 24ms | 19ms | 383.84
| UserStore.GetByUsername | p99 | 5ms | 23ms | 18ms | 360.24
| ChannelStore.GetMany | p99 | 5ms | 22ms | 17ms | 343.43
| SessionStore.GetSessionsExpired | p99 | 10ms | 24ms | 14ms | 141.41
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 19ms | 10ms | 107.14
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 10ms | 5ms | 101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 50ms | 25ms | 100.08
| PostStore.GetPostReminders | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.UpdateOptimistically | p99 | 21ms | 35ms | 14ms | 67.50
| UserStore.IsEmpty | p99 | 10ms | 16ms | 6ms | 60.63
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 8ms | 3ms | 60.61
| FileInfoStore.AttachToPost | p99 | 16ms | 25ms | 9ms | 56.65
| FileInfoStore.SetContent | p99 | 22ms | 34ms | 12ms | 55.49
| StatusStore.UpdateExpiredDNDStatuses | p99 | 12ms | 18ms | 6ms | 52.17
| DraftStore.Delete | p99 | 7ms | 10ms | 3ms | 41.98
| JobStore.Save | p99 | 5ms | 7ms | 2ms | 40.40
| LinkMetadataStore.Save | p99 | 5ms | 7ms | 2ms | 40.40
| StatusStore.SaveOrUpdate | p99 | 15ms | 20ms | 5ms | 33.34
| ThreadStore.GetThreadsForUser | p99 | 10ms | 13ms | 3ms | 31.15
| UserStore.Get | p99 | 13ms | 17ms | 4ms | 30.35
| FileInfoStore.GetByIds | p99 | 7ms | 9ms | 2ms | 30.31
| ChannelStore.GetChannels | p99 | 13ms | 17ms | 4ms | 30.10
| ChannelStore.SaveMember | p99 | 110ms | 143ms | 33ms | 30.01
| JobStore.UpdateStatus | p99 | 17ms | 22ms | 5ms | 30.00
| ChannelStore.CreateInitialSidebarCategories | p99 | 66ms | 82ms | 16ms | 24.16
| PreferenceStore.Save | p99 | 51ms | 63ms | 12ms | 23.49
| ChannelStore.GetMembersForUser | p99 | 14ms | 17ms | 3ms | 21.39
| ProductNoticesStore.View | p99 | 175ms | 212ms | 37ms | 21.14
| PostStore.GetPostsBefore | p99 | 12ms | 14ms | 2ms | 16.76
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 19ms | 22ms | 3ms | 15.97
| StatusStore.Get | p99 | 19ms | 22ms | 3ms | 15.54
| SessionStore.Save | p99 | 35ms | 40ms | 5ms | 14.46
| GroupStore.GetByName | p99 | 22ms | 25ms | 3ms | 13.68
| ChannelStore.IncrementMentionCount | p99 | 16ms | 18ms | 2ms | 12.74
| SessionStore.Get | p99 | 39ms | 44ms | 5ms | 12.74
| ChannelStore.Get | p99 | 19ms | 21ms | 2ms | 10.80
| ThreadStore.GetTotalUnreadMentions | p99 | 19ms | 21ms | 2ms | 10.52
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 19ms | 21ms | 2ms | 10.47
| UserStore.GetAllProfiles | p99 | 19ms | 21ms | 2ms | 10.34
| SystemStore.GetByName | p99 | 19ms | 21ms | 2ms | 10.28
| ThreadStore.GetTotalThreads | p99 | 20ms | 22ms | 2ms | 10.02
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 20ms | 22ms | 2ms | 9.95
| ThreadStore.GetTotalUnreadThreads | p99 | 20ms | 22ms | 2ms | 9.90
| SessionStore.GetLRUSessions | p99 | 21ms | 23ms | 2ms | 9.59
| TeamStore.SaveMember | p99 | 75ms | 82ms | 7ms | 9.36
| TeamStore.GetTeamsByUserId | p99 | 22ms | 24ms | 2ms | 9.13
| ChannelStore.GetChannelsByUser | p99 | 22ms | 24ms | 2ms | 9.09
| TeamStore.GetAllPage | p99 | 22ms | 24ms | 2ms | 8.90
| ChannelStore.GetGuestCount | p99 | 25ms | 27ms | 2ms | 8.13
| ChannelStore.GetByName | p99 | 33ms | 35ms | 2ms | 6.01
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 38ms | 40ms | 2ms | 5.31
| PostStore.Save | p99 | 43ms | 45ms | 2ms | 4.62
| UserStore.AutocompleteUsersInChannel | p99 | 157ms | 161ms | 4ms | 2.55
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -119.50
| ChannelStore.GetMembers | avg | 4ms | 0s | -4ms | -103.52
| ChannelBookmarkStore.Delete | avg | 8ms | 0s | -8ms | -102.12
| ChannelBookmarkStore.Save | avg | 9ms | 0s | -9ms | -98.11
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -82.84
| EmojiStore.GetMultipleByName | avg | 4ms | 2ms | -2ms | -53.00
| TeamStore.GetTotalMemberCount | avg | 35ms | 18ms | -17ms | -49.25
| ScheduledPostStore.GetPendingScheduledPosts | avg | 4ms | 2ms | -2ms | -47.25
| PostStore.AnalyticsPostCount | avg | 253ms | 139ms | -114ms | -44.97
| ThreadStore.MarkAllAsReadByTeam | avg | 5ms | 3ms | -2ms | -43.44
| UserStore.GetProfilesInChannel | avg | 44ms | 35ms | -9ms | -20.46
| ChannelStore.Autocomplete | avg | 43ms | 37ms | -6ms | -13.82
| ChannelStore.UpdateSidebarCategories | avg | 33ms | 31ms | -2ms | -6.03
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Save | p99 | 25ms | 0s | -25ms | -101.42
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.50
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 46ms | 5ms | -41ms | -89.62
| JobStore.GetCountByStatusAndType | p99 | 32ms | 7ms | -25ms | -78.74
| PostStore.GetPostsAfter | p99 | 39ms | 9ms | -30ms | -76.92
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 22ms | 5ms | -17ms | -75.72
| ChannelStore.Autocomplete | p99 | 393ms | 115ms | -278ms | -70.73
| ThreadStore.Get | p99 | 17ms | 5ms | -12ms | -69.75
| PostPersistentNotificationStore.Get | p99 | 21ms | 9ms | -12ms | -57.71
| PostStore.SetPostReminder | p99 | 23ms | 10ms | -13ms | -55.67
| ScheduledPostStore.CreateScheduledPost | p99 | 10ms | 5ms | -5ms | -52.36
| EmojiStore.GetMultipleByName | p99 | 10ms | 5ms | -5ms | -51.02
| UserStore.GetProfilesNotInChannel | p99 | 10ms | 5ms | -5ms | -50.76
| TeamStore.GetTotalMemberCount | p99 | 50ms | 25ms | -25ms | -50.25
| PostStore.AnalyticsPostCount | p99 | 990ms | 495ms | -495ms | -50.00
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 9ms | 5ms | -4ms | -46.65
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -44.08
| JobStore.GetNewestJobByStatusesAndType | p99 | 9ms | 5ms | -4ms | -43.24
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -43.02
| PropertyValueStore.SearchPropertyValues | p99 | 9ms | 5ms | -4ms | -42.67
| ChannelStore.AutocompleteInTeamForSearch | p99 | 460ms | 338ms | -122ms | -26.52
| ReactionStore.GetForPost | p99 | 20ms | 15ms | -5ms | -24.51
| FileInfoStore.GetForPost | p99 | 12ms | 9ms | -3ms | -24.37
| StatusStore.SaveOrUpdateMany | p99 | 58ms | 44ms | -14ms | -24.14
| ChannelStore.GetFileCount | p99 | 15ms | 12ms | -3ms | -20.37
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInAllTeams | avg | 167ms | 229ms | 62ms | 37.05
| autocompleteChannelsForTeamForSearch | avg | 46ms | 55ms | 9ms | 19.78
| getPostThread | avg | 14ms | 16ms | 2ms | 14.52
| searchPostsInTeam | avg | 122ms | 137ms | 15ms | 12.27
| getFilePreview | avg | 44ms | 47ms | 3ms | 6.85
| createUser | avg | 180ms | 189ms | 9ms | 5.00
| addTeamMember | avg | 613ms | 638ms | 25ms | 4.08
| login | avg | 85ms | 88ms | 3ms | 3.53
| removeUserCustomStatus | avg | 108ms | 111ms | 3ms | 2.77
| uploadFileStream | avg | 418ms | 429ms | 11ms | 2.63
| createPost | avg | 139ms | 142ms | 3ms | 2.16
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | p99 | 10ms | 25ms | 15ms | 150.75
| getConfig | p99 | 25ms | 50ms | 25ms | 100.60
| getPublicChannelsForTeam | p99 | 25ms | 50ms | 25ms | 100.08
| logout | p99 | 25ms | 48ms | 23ms | 92.56
| patchPost | p99 | 50ms | 83ms | 33ms | 66.32
| getFilePreview | p99 | 138ms | 221ms | 83ms | 59.98
| getPostThread | p99 | 25ms | 39ms | 14ms | 56.04
| getUsers | p99 | 24ms | 32ms | 8ms | 32.87
| getChannelsForTeamForUser | p99 | 14ms | 18ms | 4ms | 29.14
| getChannelMembersForTeamForUser | p99 | 14ms | 18ms | 4ms | 27.79
| updatePreferences | p99 | 17ms | 21ms | 4ms | 23.01
| upsertDraft | p99 | 14ms | 17ms | 3ms | 21.62
| login | p99 | 323ms | 387ms | 64ms | 19.81
| getUser | p99 | 31ms | 37ms | 6ms | 19.54
| getAllTeams | p99 | 24ms | 28ms | 4ms | 16.63
| getProfileImage | p99 | 391ms | 447ms | 56ms | 14.33
| getClientConfig | p99 | 44ms | 50ms | 6ms | 13.69
| updateReadStateThreadByUser | p99 | 79ms | 88ms | 9ms | 11.45
| getChannelStats | p99 | 28ms | 31ms | 3ms | 10.58
| getTeamsUnreadForUser | p99 | 38ms | 42ms | 4ms | 10.55
| createPost | p99 | 608ms | 668ms | 60ms | 9.86
| viewChannel | p99 | 41ms | 45ms | 4ms | 9.73
| getTeamsForUser | p99 | 22ms | 24ms | 2ms | 9.07
| getTeamMembersForUser | p99 | 23ms | 25ms | 2ms | 8.64
| getTeamScheduledPosts | p99 | 40ms | 43ms | 3ms | 7.52
| getCategoriesForTeamForUser | p99 | 41ms | 44ms | 3ms | 7.32
| addChannelMember | p99 | 420ms | 443ms | 23ms | 5.48
| getPostsForChannelAroundLastUnread | p99 | 94ms | 98ms | 4ms | 4.25
| addTeamMember | p99 | 2.226s | 2.31s | 84ms | 3.77
| saveReaction | p99 | 53ms | 55ms | 2ms | 3.76
| autocompleteUsers | p99 | 130ms | 134ms | 4ms | 3.08
| getPostsForChannel | p99 | 209ms | 215ms | 6ms | 2.87
| createUser | p99 | 476ms | 487ms | 11ms | 2.31
| getFileThumbnail | p99 | 94ms | 96ms | 2ms | 2.12
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | avg | 24ms | 0s | -24ms | -101.97
| createChannelBookmark | avg | 19ms | 0s | -19ms | -100.41
| deleteChannelBookmark | avg | 19ms | 0s | -19ms | -99.00
| getChannelMembers | avg | 4ms | 0s | -4ms | -94.77
| root | avg | 3ms | 1ms | -2ms | -70.22
| searchAllChannels | avg | 44ms | 37ms | -7ms | -16.04
| setPostReminder | avg | 32ms | 27ms | -5ms | -15.75
| createGroupChannel | avg | 281ms | 252ms | -29ms | -10.31
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| createChannelBookmark | p99 | 49ms | 0s | -49ms | -100.51
| root | p99 | 43ms | 5ms | -38ms | -88.37
| searchAllChannels | p99 | 393ms | 115ms | -278ms | -70.73
| getChannel | p99 | 21ms | 10ms | -11ms | -51.75
| autocompleteChannelsForTeamForSearch | p99 | 460ms | 338ms | -122ms | -26.52
| createDirectChannel | p99 | 422ms | 347ms | -75ms | -17.78
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.478
| BotStore.Get |  Avg| 3ms| 5ms | 2ms | 79.901
| |  P99| 5ms| 24ms | 19ms | 383.838
| ChannelBookmarkStore.Delete |  Avg| 8ms| 0s | -8ms | -102.119
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -82.839
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.654
| ChannelBookmarkStore.Save |  Avg| 9ms| 0s | -9ms | -98.109
| |  P99| 25ms| 0s | -25ms | -101.419
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.471
| ChannelStore.AnalyticsCountAll |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 43ms| 37ms | -6ms | -13.818
| |  P99| 393ms| 115ms | -278ms | -70.727
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 45ms| 55ms | 10ms | 22.006
| |  P99| 460ms| 338ms | -122ms | -26.523
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 14ms| 15ms | 1ms | 6.902
| |  P99| 66ms| 82ms | 16ms | 24.162
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.796
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.827
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 16ms | 1ms | 6.452
| |  P99| 94ms| 94ms | 0s | 0.000
| ChannelStore.GetBoardChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 35ms | 2ms | 6.007
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -38.306
| |  P99| 9ms| 5ms | -4ms | -44.077
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.097
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.090
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.122
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.367
| ChannelStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.329
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 27ms | 2ms | 8.126
| ChannelStore.GetMany |  Avg| 3ms| 4ms | 1ms | 38.635
| |  P99| 5ms| 22ms | 17ms | 343.434
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 15ms | 1ms | 6.911
| |  P99| 46ms| 47ms | 1ms | 2.174
| ChannelStore.GetMemberForPost |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 4ms| 0s | -4ms | -103.520
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.388
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 5ms | 1ms | 23.261
| |  P99| 9ms| 10ms | 1ms | 11.429
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.081
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 14ms | 1ms | 7.442
| |  P99| 25ms| 50ms | 25ms | 100.079
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 38ms| 40ms | 2ms | 5.305
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 25ms| 27ms | 2ms | 7.910
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.740
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 31ms| 32ms | 1ms | 3.212
| |  P99| 110ms| 143ms | 33ms | 30.006
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.663
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 33ms| 31ms | -2ms | -6.030
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 4ms | 1ms | 30.765
| |  P99| 9ms| 19ms | 10ms | 107.143
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 41.985
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.024
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.682
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 4ms| 2ms | -2ms | -53.000
| |  P99| 10ms| 5ms | -5ms | -51.021
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 16ms| 25ms | 9ms | 56.647
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 30.309
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -24.365
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 34ms | 12ms | 55.492
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.966
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 25ms | 3ms | 13.679
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 6.036
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 2ms| 3ms | 1ms | 41.343
| |  P99| 5ms| 10ms | 5ms | 101.010
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -30.814
| |  P99| 32ms| 7ms | -25ms | -78.740
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -39.849
| |  P99| 9ms| 5ms | -4ms | -43.243
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| JobStore.UpdateOptimistically |  Avg| 4ms| 5ms | 1ms | 24.858
| |  P99| 21ms| 35ms | 14ms | 67.502
| JobStore.UpdateStatus |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 22ms | 5ms | 29.995
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 36ms | 0s | 0.000
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.724
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.015
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -57.708
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.296
| PostPriorityStore.GetForPostWithContext |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 253ms| 139ms | -114ms | -44.972
| |  P99| 990ms| 495ms | -495ms | -50.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 2ms | 1ms | 68.157
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 13ms| 14ms | 1ms | 7.750
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.277
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.299
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.635
| PostStore.GetPostReminders |  Avg| 2ms| 3ms | 1ms | 41.949
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 4ms| 3ms | -1ms | -25.903
| |  P99| 39ms| 9ms | -30ms | -76.919
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.764
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.244
| PostStore.GetVisiblePostIdAroundTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.791
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.620
| PostStore.SearchPostsForUser |  Avg| 125ms| 152ms | 27ms | 21.552
| |  P99| 967ms| 975ms | 8ms | 0.827
| PostStore.SetPostReminder |  Avg| 7ms| 6ms | -1ms | -15.320
| |  P99| 23ms| 10ms | -13ms | -55.674
| PostStore.Update |  Avg| 12ms| 13ms | 1ms | 8.189
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 51ms| 63ms | 12ms | 23.492
| ProductNoticesStore.ClearOldNotices |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 37ms | 2ms | 5.698
| |  P99| 175ms| 212ms | 37ms | 21.135
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 3ms | 1ms | 40.224
| |  P99| 5ms| 5ms | 0s | 0.000
| PropertyGroupStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PropertyValueStore.SearchPropertyValues |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.672
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 15ms | -5ms | -24.510
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -119.497
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -101.234
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| RoleStore.GetByNames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 3ms | -1ms | -26.882
| |  P99| 10ms| 5ms | -5ms | -52.356
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 4ms| 2ms | -2ms | -47.247
| |  P99| 46ms| 5ms | -41ms | -89.617
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.626
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 2ms | -1ms | -39.863
| |  P99| 22ms| 5ms | -17ms | -75.724
| SchemeStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 39ms| 44ms | 5ms | 12.739
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.589
| SessionStore.GetSessionsExpired |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 141.414
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 35ms| 40ms | 5ms | 14.461
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.535
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 3ms| 4ms | 1ms | 28.948
| |  P99| 15ms| 20ms | 5ms | 33.336
| StatusStore.SaveOrUpdateMany |  Avg| 6ms| 8ms | 2ms | 31.330
| |  P99| 58ms| 44ms | -14ms | -24.143
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 18ms | 6ms | 52.174
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.125
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.279
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 3ms | 1ms | 40.063
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.896
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.511
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.127
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.543
| TeamStore.GetTotalMemberCount |  Avg| 35ms| 18ms | -17ms | -49.249
| |  P99| 50ms| 25ms | -25ms | -50.251
| TeamStore.SaveMember |  Avg| 22ms| 23ms | 1ms | 4.520
| |  P99| 75ms| 82ms | 7ms | 9.359
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 3ms| 2ms | -1ms | -39.539
| |  P99| 17ms| 5ms | -12ms | -69.754
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.803
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.404
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 31.153
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 10.025
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.517
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.903
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.952
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.559
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -38.999
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 5ms| 3ms | -2ms | -43.437
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.466
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.562
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 157ms| 161ms | 4ms | 2.545
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.220
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.345
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.336
| UserStore.GetAllProfilesInChannel |  Avg| 152ms| 156ms | 4ms | 2.627
| |  P99| 476ms| 479ms | 3ms | 0.630
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 23ms | 18ms | 360.237
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.474
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 41.659
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.389
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.164
| UserStore.GetProfilesInChannel |  Avg| 44ms| 35ms | -9ms | -20.464
| |  P99| 246ms| 244ms | -2ms | -0.815
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.761
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.767
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.631
| UserStore.Save |  Avg| 120ms| 124ms | 4ms | 3.343
| |  P99| 248ms| 249ms | 1ms | 0.403
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.853
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.950
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 5ms | 1ms | 22.823
| |  P99| 24ms| 25ms | 1ms | 4.099
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.578
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.562
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.021
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 181ms| 180ms | -1ms | -0.554
| | P99| 420ms| 443ms | 23ms | 5.476
| addTeamMember | Avg| 613ms| 638ms | 25ms | 4.080
| | P99| 2.226s| 2.31s | 84ms | 3.773
| autocompleteChannelsForTeamForSearch | Avg| 46ms| 55ms | 9ms | 19.776
| | P99| 460ms| 338ms | -122ms | -26.523
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 130ms| 134ms | 4ms | 3.080
| createChannel | Avg| 207ms| 209ms | 2ms | 0.966
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 19ms| 0s | -19ms | -100.414
| | P99| 49ms| 0s | -49ms | -100.514
| createDirectChannel | Avg| 168ms| 167ms | -1ms | -0.597
| | P99| 422ms| 347ms | -75ms | -17.777
| createGroupChannel | Avg| 281ms| 252ms | -29ms | -10.312
| | P99| 497ms| 496ms | -1ms | -0.201
| createPost | Avg| 139ms| 142ms | 3ms | 2.160
| | P99| 608ms| 668ms | 60ms | 9.864
| createSchedulePost | Avg| 5ms| 4ms | -1ms | -21.760
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 180ms| 189ms | 9ms | 4.996
| | P99| 476ms| 487ms | 11ms | 2.313
| deleteChannelBookmark | Avg| 19ms| 0s | -19ms | -99.004
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.702
| deletePost | Avg| 20ms| 21ms | 1ms | 5.123
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 12ms| 13ms | 1ms | 8.146
| | P99| 25ms| 25ms | 0s | 0.000
| getAgents | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAgentsStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 28ms | 4ms | 16.625
| getAnalytics | Avg| 45ms| 46ms | 1ms | 2.218
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 7ms| 8ms | 1ms | 14.007
| | P99| 41ms| 44ms | 3ms | 7.322
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 21ms| 10ms | -11ms | -51.752
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 45ms| 46ms | 1ms | 2.211
| getChannelMembers | Avg| 4ms| 0s | -4ms | -94.767
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 4ms | 1ms | 28.618
| | P99| 14ms| 18ms | 4ms | 27.791
| getChannelMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 31ms | 3ms | 10.582
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.485
| getChannelsForTeamForUser | Avg| 3ms| 4ms | 1ms | 31.010
| | P99| 14ms| 18ms | 4ms | 29.144
| getChannelsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.436
| getClientConfig | Avg| 6ms| 7ms | 1ms | 16.455
| | P99| 44ms| 50ms | 6ms | 13.688
| getConfig | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 25ms| 50ms | 25ms | 100.604
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getFilePreview | Avg| 44ms| 47ms | 3ms | 6.850
| | P99| 138ms| 221ms | 83ms | 59.976
| getFileThumbnail | Avg| 40ms| 41ms | 1ms | 2.483
| | P99| 94ms| 96ms | 2ms | 2.118
| getFilteredUsersStats | Avg| 10ms| 11ms | 1ms | 9.789
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 14ms| 16ms | 2ms | 14.517
| | P99| 25ms| 39ms | 14ms | 56.042
| getPostsForChannel | Avg| 26ms| 27ms | 1ms | 3.868
| | P99| 209ms| 215ms | 6ms | 2.870
| getPostsForChannelAroundLastUnread | Avg| 21ms| 22ms | 1ms | 4.805
| | P99| 94ms| 98ms | 4ms | 4.247
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.132
| getPrevTrialLicense | Avg| 1ms| 2ms | 1ms | 79.923
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 91ms| 91ms | 0s | 0.000
| | P99| 391ms| 447ms | 56ms | 14.331
| getPropertyFields | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 14ms| 15ms | 1ms | 7.019
| | P99| 25ms| 50ms | 25ms | 100.079
| getRolesByNames | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 25ms | 15ms | 150.754
| getServerLimits | Avg| 11ms| 12ms | 1ms | 9.372
| | P99| 25ms| 25ms | 0s | 0.000
| getSystemPropertyValues | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.787
| getTeamMembersForUser | Avg| 3ms| 4ms | 1ms | 29.291
| | P99| 23ms| 25ms | 2ms | 8.642
| getTeamScheduledPosts | Avg| 6ms| 7ms | 1ms | 16.165
| | P99| 40ms| 43ms | 3ms | 7.519
| getTeamStats | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 4ms | 1ms | 30.441
| | P99| 22ms| 24ms | 2ms | 9.072
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 38ms| 42ms | 4ms | 10.550
| getThreadsForUser | Avg| 4ms| 5ms | 1ms | 23.776
| | P99| 22ms| 23ms | 1ms | 4.547
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 31ms| 37ms | 6ms | 19.536
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 32ms | 8ms | 32.869
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 4ms | 1ms | 34.677
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 85ms| 88ms | 3ms | 3.526
| | P99| 323ms| 387ms | 64ms | 19.808
| logout | Avg| 23ms| 24ms | 1ms | 4.433
| | P99| 25ms| 48ms | 23ms | 92.555
| patchPost | Avg| 30ms| 31ms | 1ms | 3.341
| | P99| 50ms| 83ms | 33ms | 66.323
| removeUserCustomStatus | Avg| 108ms| 111ms | 3ms | 2.773
| | P99| 247ms| 248ms | 1ms | 0.404
| root | Avg| 3ms| 1ms | -2ms | -70.219
| | P99| 43ms| 5ms | -38ms | -88.372
| saveReaction | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 53ms| 55ms | 2ms | 3.759
| searchAllChannels | Avg| 44ms| 37ms | -7ms | -16.035
| | P99| 393ms| 115ms | -278ms | -70.727
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.663
| searchPostsInAllTeams | Avg| 167ms| 229ms | 62ms | 37.050
| | P99| 974ms| 983ms | 9ms | 0.924
| searchPostsInTeam | Avg| 122ms| 137ms | 15ms | 12.272
| | P99| 978ms| 974ms | -4ms | -0.409
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 49ms| 50ms | 1ms | 2.020
| setPostReminder | Avg| 32ms| 27ms | -5ms | -15.749
| | P99| 50ms| 50ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 51ms| 51ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| updateChannelBookmark | Avg| 24ms| 0s | -24ms | -101.971
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 17ms| 21ms | 4ms | 23.008
| updateReadStateAllThreadsByUser | Avg| 5ms| 4ms | -1ms | -21.187
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 37ms| 38ms | 1ms | 2.705
| | P99| 79ms| 88ms | 9ms | 11.454
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 418ms| 429ms | 11ms | 2.634
| | P99| 990ms| 992ms | 2ms | 0.202
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 14ms| 17ms | 3ms | 21.616
| viewChannel | Avg| 14ms| 15ms | 1ms | 7.002
| | P99| 41ms| 45ms | 4ms | 9.731
