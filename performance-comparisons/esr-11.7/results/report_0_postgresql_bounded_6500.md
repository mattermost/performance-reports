### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 140ms | 138ms | 5734.95
| ChannelStore.GetTeamChannels | avg | 10ms | 16ms | 6ms | 59.65
| UserStore.Save | avg | 79ms | 124ms | 45ms | 57.11
| ChannelStore.AutocompleteInTeamForSearch | avg | 30ms | 45ms | 15ms | 50.54
| ChannelStore.Save | avg | 9ms | 11ms | 2ms | 21.16
| ChannelStore.Autocomplete | avg | 32ms | 37ms | 5ms | 15.78
| ChannelStore.UpdateSidebarCategories | avg | 28ms | 32ms | 4ms | 14.12
| PostStore.SearchPostsForUser | avg | 21ms | 24ms | 3ms | 14.09
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 495ms | 490ms | 9896.47
| JobStore.UpdateOptimistically | p99 | 9ms | 71ms | 62ms | 670.27
| BotStore.Get | p99 | 5ms | 23ms | 18ms | 363.64
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 22ms | 17ms | 343.43
| PostStore.GetPostReminderMetadata | p99 | 5ms | 22ms | 17ms | 343.41
| ChannelStore.Save | p99 | 24ms | 65ms | 41ms | 169.42
| ChannelStore.AutocompleteInTeamForSearch | p99 | 175ms | 428ms | 253ms | 144.59
| ChannelStore.Autocomplete | p99 | 99ms | 239ms | 140ms | 141.73
| PostPersistentNotificationStore.Get | p99 | 9ms | 21ms | 12ms | 140.35
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 93ms | 43ms | 86.48
| UserAccessTokenStore.GetByToken | p99 | 5ms | 9ms | 4ms | 80.79
| FileInfoStore.SetContent | p99 | 21ms | 38ms | 17ms | 79.55
| ReactionStore.GetForPost | p99 | 10ms | 16ms | 6ms | 62.06
| UserStore.GetMany | p99 | 5ms | 8ms | 3ms | 60.61
| PropertyValueStore.SearchPropertyValues | p99 | 10ms | 15ms | 5ms | 51.61
| UserStore.GetUnreadCount | p99 | 10ms | 13ms | 3ms | 28.99
| ChannelStore.SaveMember | p99 | 99ms | 116ms | 17ms | 17.22
| JobStore.GetAllByStatus | p99 | 17ms | 19ms | 2ms | 11.64
| UserStore.Save | p99 | 225ms | 249ms | 24ms | 10.65
| UserStore.AutocompleteUsersInChannel | p99 | 158ms | 173ms | 15ms | 9.48
| ChannelStore.GetChannelsByUser | p99 | 21ms | 23ms | 2ms | 9.37
| UserStore.UpdateUpdateAt | p99 | 22ms | 24ms | 2ms | 9.04
| ChannelStore.CreateInitialSidebarCategories | p99 | 66ms | 68ms | 2ms | 3.02
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -124.76
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -105.09
| ChannelStore.CreateSidebarCategory | avg | 15ms | 0s | -15ms | -98.12
| SharedChannelStore.HasChannel | avg | 2ms | 0s | -2ms | -97.76
| ChannelStore.IsReadOnlyChannel | avg | 2ms | 0s | -2ms | -92.76
| PostPriorityStore.GetForPost | avg | 2ms | 0s | -2ms | -88.64
| UserStore.GetProfilesInChannel | avg | 34ms | 10ms | -24ms | -70.11
| PostStore.GetPostReminders | avg | 5ms | 2ms | -3ms | -64.12
| UserStore.GetAllProfilesInChannel | avg | 157ms | 149ms | -8ms | -5.08
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPriorityStore.GetForPost | p99 | 10ms | 0s | -10ms | -104.71
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.IsReadOnlyChannel | p99 | 9ms | 0s | -9ms | -96.37
| SharedChannelStore.HasChannel | p99 | 8ms | 0s | -8ms | -96.02
| UserStore.GetProfilesInChannel | p99 | 244ms | 25ms | -219ms | -89.75
| ClusterDiscoveryStore.SetLastPingAt | p99 | 56ms | 7ms | -49ms | -88.29
| StatusStore.UpdateExpiredDNDStatuses | p99 | 55ms | 9ms | -46ms | -82.88
| PostAcknowledgementStore.GetForPost | p99 | 20ms | 5ms | -15ms | -74.26
| JobStore.GetCountByStatusAndType | p99 | 21ms | 9ms | -12ms | -58.54
| JobStore.UpdateStatusOptimistically | p99 | 39ms | 17ms | -22ms | -56.77
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 5ms | -5ms | -52.04
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 5ms | -5ms | -51.81
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 10ms | 5ms | -5ms | -51.28
| PostStore.GetPostReminders | p99 | 10ms | 5ms | -5ms | -50.72
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.90
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 5ms | -4ms | -46.78
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -46.24
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -45.98
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 84ms | 48ms | -36ms | -42.90
| UserStore.Update | p99 | 17ms | 10ms | -7ms | -40.82
| UserStore.GetByUsername | p99 | 16ms | 10ms | -6ms | -37.15
| StatusStore.SaveOrUpdate | p99 | 23ms | 17ms | -6ms | -26.20
| FileInfoStore.GetByIds | p99 | 12ms | 9ms | -3ms | -24.29
| StatusStore.SaveOrUpdateMany | p99 | 48ms | 37ms | -11ms | -22.80
| ThreadStore.GetThreadsForUser | p99 | 14ms | 11ms | -3ms | -20.95
| FileInfoStore.Save | p99 | 18ms | 15ms | -3ms | -16.89
| UserStore.UpdateFailedPasswordAttempts | p99 | 30ms | 25ms | -5ms | -16.41
| PreferenceStore.Save | p99 | 58ms | 50ms | -8ms | -13.90
| FileInfoStore.AttachToPost | p99 | 19ms | 17ms | -2ms | -10.59
| PostStore.GetPostIdAfterTime | p99 | 19ms | 17ms | -2ms | -10.40
| ChannelStore.GetByName | p99 | 42ms | 38ms | -4ms | -9.52
| TeamStore.GetMember | p99 | 22ms | 20ms | -2ms | -9.28
| SessionStore.Get | p99 | 45ms | 41ms | -4ms | -8.94
| ChannelStore.SearchGroupChannels | p99 | 23ms | 21ms | -2ms | -8.73
| ChannelStore.GetAllChannelMembersForUser | p99 | 24ms | 22ms | -2ms | -8.46
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 38ms | 36ms | -2ms | -5.31
| TeamStore.SaveMember | p99 | 82ms | 78ms | -4ms | -4.90
| ProductNoticesStore.View | p99 | 191ms | 188ms | -3ms | -1.57
| UserStore.GetAllProfilesInChannel | p99 | 480ms | 474ms | -6ms | -1.25
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAValues | avg | 2ms | 5ms | 3ms | 128.97
| listCPAFields | avg | 3ms | 6ms | 3ms | 97.68
| autocompleteChannelsForTeamForSearch | avg | 30ms | 45ms | 15ms | 50.43
| login | avg | 70ms | 104ms | 34ms | 48.77
| createUser | avg | 197ms | 246ms | 49ms | 24.87
| setPostReminder | avg | 16ms | 19ms | 3ms | 19.32
| followThreadByUser | avg | 10ms | 12ms | 2ms | 19.24
| searchAllChannels | avg | 32ms | 37ms | 5ms | 15.68
| createChannelBookmark | avg | 13ms | 15ms | 2ms | 15.35
| createChannel | avg | 168ms | 193ms | 25ms | 14.92
| createGroupChannel | avg | 251ms | 278ms | 27ms | 10.77
| searchPostsInTeam | avg | 30ms | 33ms | 3ms | 9.95
| getPostsForChannel | avg | 21ms | 23ms | 2ms | 9.59
| updateCategoriesForTeamForUser | avg | 46ms | 50ms | 4ms | 8.79
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAValues | p99 | 10ms | 25ms | 15ms | 154.22
| autocompleteChannelsForTeamForSearch | p99 | 175ms | 428ms | 253ms | 144.59
| searchAllChannels | p99 | 99ms | 239ms | 140ms | 141.73
| getChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| listCPAFields | p99 | 23ms | 41ms | 18ms | 77.57
| login | p99 | 354ms | 496ms | 142ms | 40.06
| saveReaction | p99 | 28ms | 35ms | 7ms | 25.42
| getPostThread | p99 | 25ms | 31ms | 6ms | 24.02
| autocompleteUsers | p99 | 131ms | 154ms | 23ms | 17.53
| getUsers | p99 | 25ms | 29ms | 4ms | 15.69
| getPostsForChannel | p99 | 180ms | 202ms | 22ms | 12.22
| getUser | p99 | 36ms | 40ms | 4ms | 11.19
| createUser | p99 | 925ms | 958ms | 33ms | 3.57
| updateCategoriesForTeamForUser | p99 | 95ms | 98ms | 3ms | 3.17
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 19ms | 0s | -19ms | -101.55
| viewChannel | avg | 11ms | 9ms | -2ms | -17.77
| logout | avg | 25ms | 21ms | -4ms | -15.72
| deletePost | avg | 21ms | 19ms | -2ms | -9.71
| getProfileImage | avg | 105ms | 96ms | -9ms | -8.58
| createPost | avg | 158ms | 147ms | -11ms | -6.94
| addTeamMember | avg | 637ms | 600ms | -37ms | -5.80
| createDirectChannel | avg | 173ms | 166ms | -7ms | -4.04
| uploadFileStream | avg | 446ms | 428ms | -18ms | -4.03
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| getFilteredUsersStats | p99 | 25ms | 10ms | -15ms | -60.36
| getRolesByNames | p99 | 10ms | 5ms | -5ms | -50.25
| getPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.90
| logout | p99 | 49ms | 25ms | -24ms | -48.73
| getChannel | p99 | 24ms | 15ms | -9ms | -37.90
| createDirectChannel | p99 | 455ms | 341ms | -114ms | -25.04
| getFilePreview | p99 | 153ms | 115ms | -38ms | -24.87
| viewChannel | p99 | 41ms | 31ms | -10ms | -24.25
| getTeamMember | p99 | 10ms | 8ms | -2ms | -21.05
| getFileThumbnail | p99 | 119ms | 99ms | -20ms | -16.75
| updatePreferences | p99 | 21ms | 18ms | -3ms | -14.33
| createPost | p99 | 742ms | 659ms | -83ms | -11.18
| addTeamMember | p99 | 2.262s | 2.122s | -140ms | -6.19
| getTeamScheduledPosts | p99 | 40ms | 38ms | -2ms | -4.95
| getTeamsUnreadForUser | p99 | 41ms | 39ms | -2ms | -4.88
| getClientConfig | p99 | 47ms | 45ms | -2ms | -4.23
| getChannelMember | p99 | 48ms | 46ms | -2ms | -4.19
| getPostsForChannelAroundLastUnread | p99 | 93ms | 91ms | -2ms | -2.16
| getProfileImage | p99 | 480ms | 472ms | -8ms | -1.67
| addChannelMember | p99 | 397ms | 392ms | -5ms | -1.26
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 50.040
| |  P99| 5ms| 23ms | 18ms | 363.636
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.175
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 37ms | 5ms | 15.783
| |  P99| 99ms| 239ms | 140ms | 141.727
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 30ms| 45ms | 15ms | 50.539
| |  P99| 175ms| 428ms | 253ms | 144.591
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 21ms | 1ms | 5.039
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.CreateInitialSidebarCategories |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 66ms| 68ms | 2ms | 3.018
| ChannelStore.CreateSidebarCategory |  Avg| 15ms| 0s | -15ms | -98.117
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 3ms | -1ms | -27.877
| |  P99| 24ms| 22ms | -2ms | -8.458
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 84ms| 48ms | -36ms | -42.899
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 38ms | -4ms | -9.521
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -6.018
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.373
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.641
| ChannelStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.600
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.099
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.282
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.143
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 25ms | -24ms | -48.901
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.308
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 8ms | 1ms | 13.637
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 10ms| 16ms | 6ms | 59.649
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 0s | -2ms | -92.763
| |  P99| 9ms| 0s | -9ms | -96.368
| ChannelStore.Save |  Avg| 9ms| 11ms | 2ms | 21.160
| |  P99| 24ms| 65ms | 41ms | 169.421
| ChannelStore.SaveMember |  Avg| 29ms| 30ms | 1ms | 3.484
| |  P99| 99ms| 116ms | 17ms | 17.218
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.730
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 32ms | 4ms | 14.124
| |  P99| 50ms| 93ms | 43ms | 86.476
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -27.897
| |  P99| 56ms| 7ms | -49ms | -88.288
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.754
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 5ms | 1ms | 25.382
| |  P99| 24ms| 24ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.298
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.093
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.595
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.757
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -24.291
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.110
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.889
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 38ms | 17ms | 79.551
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.482
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.286
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.927
| JobStore.GetAllByStatus |  Avg| 2ms| 3ms | 1ms | 41.600
| |  P99| 17ms| 19ms | 2ms | 11.641
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -58.537
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.813
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.987
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 71ms | 62ms | 670.270
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.479
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 17ms | -22ms | -56.774
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.799
| |  P99| 20ms| 5ms | -15ms | -74.260
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.784
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 140.351
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 0s | -2ms | -88.636
| |  P99| 10ms| 0s | -10ms | -104.713
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.818
| PostStore.AnalyticsPostCount |  Avg| 2ms| 140ms | 138ms | 5734.946
| |  P99| 5ms| 495ms | 490ms | 9896.474
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.279
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.239
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.402
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.010
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 343.408
| PostStore.GetPostReminders |  Avg| 5ms| 2ms | -3ms | -64.123
| |  P99| 10ms| 5ms | -5ms | -50.719
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.209
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.241
| PostStore.GetPostsBefore |  Avg| 4ms| 3ms | -1ms | -28.550
| |  P99| 13ms| 12ms | -1ms | -7.896
| PostStore.GetPostsByThread |  Avg| 6ms| 5ms | -1ms | -17.775
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.327
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 21ms| 24ms | 3ms | 14.090
| |  P99| 532ms| 533ms | 1ms | 0.188
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 2ms | -1ms | -31.184
| |  P99| 10ms| 5ms | -5ms | -52.038
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 58ms| 50ms | -8ms | -13.902
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 34ms | -1ms | -2.860
| |  P99| 191ms| 188ms | -3ms | -1.570
| PropertyFieldStore.SearchPropertyFields |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.530
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 51.615
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 62.060
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -124.762
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -109.989
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 3ms | 1ms | 49.305
| |  P99| 5ms| 22ms | 17ms | 343.434
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -105.090
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 6ms| 5ms | -1ms | -17.752
| |  P99| 45ms| 41ms | -4ms | -8.937
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.504
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 2ms | -1ms | -38.416
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.616
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 0s | -2ms | -97.759
| |  P99| 8ms| 0s | -8ms | -96.015
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.788
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 3ms | -1ms | -28.507
| |  P99| 23ms| 17ms | -6ms | -26.195
| StatusStore.SaveOrUpdateMany |  Avg| 7ms| 6ms | -1ms | -14.170
| |  P99| 48ms| 37ms | -11ms | -22.801
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 2ms | -1ms | -31.004
| |  P99| 55ms| 9ms | -46ms | -82.883
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.664
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 3ms| 2ms | -1ms | -39.776
| |  P99| 22ms| 20ms | -2ms | -9.281
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 34ms| 33ms | -1ms | -2.932
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 23ms| 22ms | -1ms | -4.333
| |  P99| 82ms| 78ms | -4ms | -4.903
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.076
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -20.953
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.648
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.634
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.378
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.978
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.008
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 1ms | -1ms | -63.859
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.785
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 158ms| 173ms | 15ms | 9.483
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.046
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 157ms| 149ms | -8ms | -5.084
| |  P99| 480ms| 474ms | -6ms | -1.251
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.151
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.656
| UserStore.GetProfilesInChannel |  Avg| 34ms| 10ms | -24ms | -70.110
| |  P99| 244ms| 25ms | -219ms | -89.754
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 28.986
| UserStore.IsEmpty |  Avg| 1ms| 2ms | 1ms | 67.515
| |  P99| 14ms| 15ms | 1ms | 6.972
| UserStore.Save |  Avg| 79ms| 124ms | 45ms | 57.114
| |  P99| 225ms| 249ms | 24ms | 10.649
| UserStore.Search |  Avg| 25ms| 26ms | 1ms | 3.924
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -40.823
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 25ms | -5ms | -16.406
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.042
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.140
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 164ms| 164ms | 0s | 0.000
| | P99| 397ms| 392ms | -5ms | -1.260
| addTeamMember | Avg| 637ms| 600ms | -37ms | -5.804
| | P99| 2.262s| 2.122s | -140ms | -6.190
| autocompleteChannelsForTeamForSearch | Avg| 30ms| 45ms | 15ms | 50.430
| | P99| 175ms| 428ms | 253ms | 144.591
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 131ms| 154ms | 23ms | 17.529
| createCategoryForTeamForUser | Avg| 19ms| 0s | -19ms | -101.554
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 168ms| 193ms | 25ms | 14.916
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 13ms| 15ms | 2ms | 15.351
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 173ms| 166ms | -7ms | -4.040
| | P99| 455ms| 341ms | -114ms | -25.035
| createGroupChannel | Avg| 251ms| 278ms | 27ms | 10.774
| | P99| 495ms| 497ms | 2ms | 0.404
| createPost | Avg| 158ms| 147ms | -11ms | -6.942
| | P99| 742ms| 659ms | -83ms | -11.182
| createSchedulePost | Avg| 3ms| 4ms | 1ms | 30.426
| | P99| 9ms| 10ms | 1ms | 11.131
| createUser | Avg| 197ms| 246ms | 49ms | 24.870
| | P99| 925ms| 958ms | 33ms | 3.569
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 21ms| 19ms | -2ms | -9.706
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 12ms | 2ms | 19.241
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.005
| getCategoriesForTeamForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 40ms| 40ms | 0s | 0.000
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 24ms| 15ms | -9ms | -37.896
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 48ms| 46ms | -2ms | -4.192
| getChannelMembers | Avg| 3ms| 4ms | 1ms | 30.729
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 30ms| 31ms | 1ms | 3.312
| getChannelUnread | Avg| 2ms| 3ms | 1ms | 45.044
| | P99| 5ms| 9ms | 4ms | 80.808
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -5.905
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.633
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 47ms| 45ms | -2ms | -4.228
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| getFilePreview | Avg| 46ms| 45ms | -1ms | -2.179
| | P99| 153ms| 115ms | -38ms | -24.871
| getFileThumbnail | Avg| 44ms| 43ms | -1ms | -2.275
| | P99| 119ms| 99ms | -20ms | -16.746
| getFilteredUsersStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 10ms | -15ms | -60.362
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 12ms| 13ms | 1ms | 8.000
| | P99| 25ms| 31ms | 6ms | 24.018
| getPostsForChannel | Avg| 21ms| 23ms | 2ms | 9.590
| | P99| 180ms| 202ms | 22ms | 12.217
| getPostsForChannelAroundLastUnread | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 93ms| 91ms | -2ms | -2.158
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.110
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 105ms| 96ms | -9ms | -8.583
| | P99| 480ms| 472ms | -8ms | -1.665
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 49ms| 25ms | -24ms | -48.901
| getRolesByNames | Avg| 6ms| 5ms | -1ms | -17.976
| | P99| 10ms| 5ms | -5ms | -50.251
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 8ms | -2ms | -21.052
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 40ms| 38ms | -2ms | -4.951
| getTeamStats | Avg| 35ms| 34ms | -1ms | -2.885
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 6ms| 5ms | -1ms | -18.033
| | P99| 41ms| 39ms | -2ms | -4.883
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.327
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 36ms| 40ms | 4ms | 11.192
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 29ms | 4ms | 15.689
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 6ms | 3ms | 97.678
| | P99| 23ms| 41ms | 18ms | 77.567
| listCPAValues | Avg| 2ms| 5ms | 3ms | 128.965
| | P99| 10ms| 25ms | 15ms | 154.224
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 70ms| 104ms | 34ms | 48.766
| | P99| 354ms| 496ms | 142ms | 40.062
| logout | Avg| 25ms| 21ms | -4ms | -15.715
| | P99| 49ms| 25ms | -24ms | -48.731
| patchPost | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| removeUserCustomStatus | Avg| 110ms| 109ms | -1ms | -0.911
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 0s| 1ms | 1ms | 685.548
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 28ms| 35ms | 7ms | 25.416
| searchAllChannels | Avg| 32ms| 37ms | 5ms | 15.677
| | P99| 99ms| 239ms | 140ms | 141.727
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.356
| searchPostsInTeam | Avg| 30ms| 33ms | 3ms | 9.950
| | P99| 532ms| 533ms | 1ms | 0.188
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 19ms | 3ms | 19.318
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 46ms| 50ms | 4ms | 8.789
| | P99| 95ms| 98ms | 3ms | 3.175
| updatePreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 21ms| 18ms | -3ms | -14.327
| updateReadStateThreadByUser | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 88ms| 88ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 446ms| 428ms | -18ms | -4.033
| | P99| 992ms| 993ms | 1ms | 0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| viewChannel | Avg| 11ms| 9ms | -2ms | -17.770
| | P99| 41ms| 31ms | -10ms | -24.248
