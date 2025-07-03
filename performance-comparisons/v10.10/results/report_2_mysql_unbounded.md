### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.Count | avg | 64ms | 80ms | 16ms | 24.88
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 11ms | 13ms | 2ms | 17.57
| ChannelStore.AutocompleteInTeamForSearch | avg | 183ms | 209ms | 26ms | 14.24
| ChannelStore.CreateSidebarCategory | avg | 16ms | 18ms | 2ms | 12.69
| TeamStore.GetTotalMemberCount | avg | 86ms | 88ms | 2ms | 2.31
| ChannelStore.Autocomplete | avg | 969ms | 989ms | 20ms | 2.06
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetCountByStatusAndType | p99 | 9ms | 59ms | 50ms | 575.82
| JobStore.Save | p99 | 9ms | 32ms | 23ms | 263.86
| UserStore.GetMany | p99 | 8ms | 20ms | 12ms | 151.90
| TeamStore.GetTotalMemberCount | p99 | 100ms | 238ms | 138ms | 138.69
| UserStore.Count | p99 | 99ms | 232ms | 133ms | 133.98
| UserStore.Update | p99 | 10ms | 20ms | 10ms | 100.01
| ChannelStore.UpdateSidebarCategories | p99 | 49ms | 85ms | 36ms | 74.23
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 70ms | 94ms | 24ms | 34.43
| UserStore.GetByUsername | p99 | 7ms | 9ms | 2ms | 29.56
| UserStore.UpdateUpdateAt | p99 | 10ms | 12ms | 2ms | 19.62
| JobStore.UpdateStatus | p99 | 13ms | 15ms | 2ms | 14.87
| UserStore.AutocompleteUsersInChannel | p99 | 358ms | 381ms | 23ms | 6.43
| ChannelStore.CreateDirectChannel | p99 | 45ms | 47ms | 2ms | 4.47
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.225s | 2.306s | 81ms | 3.64
| StatusStore.SaveOrUpdate | p99 | 205ms | 210ms | 5ms | 2.44
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberCountsByGroup | avg | 2ms | 0s | -2ms | -118.43
| ChannelBookmarkStore.UpdateSortOrder | avg | 5ms | 0s | -5ms | -94.71
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 3ms | 0s | -3ms | -86.56
| CommandWebhookStore.Cleanup | avg | 3ms | 1ms | -2ms | -79.92
| PostStore.AnalyticsPostCount | avg | 788ms | 169ms | -619ms | -78.60
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 4ms | 2ms | -2ms | -53.36
| ThreadStore.MarkAllAsReadByTeam | avg | 6ms | 3ms | -3ms | -49.80
| ChannelBookmarkStore.Save | avg | 14ms | 8ms | -6ms | -43.96
| ScheduledPostStore.CreateScheduledPost | avg | 5ms | 3ms | -2ms | -41.52
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 16ms | 13ms | -3ms | -19.22
| PostStore.SearchPostsForUser | avg | 66ms | 59ms | -7ms | -10.57
| UserStore.AnalyticsActiveCount | avg | 157ms | 142ms | -15ms | -9.58
| ProductNoticesStore.View | avg | 26ms | 24ms | -2ms | -7.79
| ChannelStore.GetMemberCount | avg | 76ms | 73ms | -3ms | -3.96
| UserStore.GetAllProfilesInChannel | avg | 259ms | 249ms | -10ms | -3.87
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.96
| ChannelBookmarkStore.UpdateSortOrder | p99 | 10ms | 0s | -10ms | -100.76
| RoleStore.ChannelHigherScopedPermissions | p99 | 38ms | 5ms | -33ms | -86.84
| ChannelStore.GetSidebarCategory | p99 | 76ms | 16ms | -60ms | -78.95
| ScheduledPostStore.CreateScheduledPost | p99 | 43ms | 9ms | -34ms | -78.61
| PostStore.SearchPostsForUser | p99 | 1.313s | 461ms | -852ms | -64.88
| PostStore.GetPostReminders | p99 | 24ms | 10ms | -14ms | -59.32
| BotStore.Get | p99 | 21ms | 9ms | -12ms | -58.11
| StatusStore.UpdateExpiredDNDStatuses | p99 | 23ms | 10ms | -13ms | -57.02
| PluginStore.List | p99 | 36ms | 17ms | -19ms | -53.52
| CommandWebhookStore.Cleanup | p99 | 10ms | 5ms | -5ms | -51.02
| ChannelBookmarkStore.Save | p99 | 47ms | 24ms | -23ms | -49.20
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 9ms | 5ms | -4ms | -46.51
| UserStore.GetProfilesInChannel | p99 | 9ms | 5ms | -4ms | -46.24
| UserAccessTokenStore.GetByToken | p99 | 9ms | 5ms | -4ms | -45.45
| PostStore.Delete | p99 | 44ms | 25ms | -19ms | -42.70
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 44ms | 25ms | -19ms | -42.70
| PostPriorityStore.GetForPost | p99 | 16ms | 9ms | -7ms | -42.68
| JobStore.GetAllByStatus | p99 | 17ms | 10ms | -7ms | -40.21
| PostPersistentNotificationStore.DeleteExpired | p99 | 8ms | 5ms | -3ms | -39.22
| PostAcknowledgementStore.GetForPost | p99 | 16ms | 10ms | -6ms | -36.59
| FileInfoStore.AttachToPost | p99 | 17ms | 11ms | -6ms | -35.21
| JobStore.UpdateOptimistically | p99 | 13ms | 9ms | -4ms | -29.74
| FileInfoStore.Get | p99 | 8ms | 6ms | -2ms | -26.57
| WebhookStore.GetOutgoingByTeam | p99 | 34ms | 25ms | -9ms | -26.34
| ChannelStore.UpdateLastViewedAt | p99 | 16ms | 12ms | -4ms | -24.79
| UserStore.GetUnreadCount | p99 | 28ms | 21ms | -7ms | -24.60
| FileInfoStore.SetContent | p99 | 29ms | 22ms | -7ms | -23.80
| ChannelStore.GetMember | p99 | 9ms | 7ms | -2ms | -23.47
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 9ms | 7ms | -2ms | -23.35
| FileInfoStore.Save | p99 | 17ms | 13ms | -4ms | -23.14
| DraftStore.Get | p99 | 9ms | 7ms | -2ms | -22.17
| ChannelStore.GetMemberForPost | p99 | 9ms | 7ms | -2ms | -21.91
| JobStore.GetNewestJobByStatusesAndType | p99 | 9ms | 7ms | -2ms | -21.23
| JobStore.UpdateStatusOptimistically | p99 | 19ms | 15ms | -4ms | -20.81
| ChannelStore.SaveMember | p99 | 67ms | 54ms | -13ms | -19.52
| PluginStore.SetWithOptions | p99 | 16ms | 13ms | -3ms | -18.25
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 12ms | 10ms | -2ms | -16.88
| ThreadStore.GetTotalUnreadMentions | p99 | 12ms | 10ms | -2ms | -16.66
| ChannelStore.GetAllChannelMembersForUser | p99 | 18ms | 15ms | -3ms | -16.41
| ThreadStore.MaintainMembership | p99 | 18ms | 15ms | -3ms | -16.38
| SessionStore.Get | p99 | 21ms | 18ms | -3ms | -14.53
| AuditStore.Save | p99 | 17ms | 15ms | -2ms | -11.83
| ThreadStore.GetThreadForUser | p99 | 17ms | 15ms | -2ms | -11.65
| PostStore.Get | p99 | 17ms | 15ms | -2ms | -11.43
| PostStore.Save | p99 | 41ms | 37ms | -4ms | -9.66
| SessionStore.Save | p99 | 21ms | 19ms | -2ms | -9.64
| ChannelStore.GetByName | p99 | 25ms | 23ms | -2ms | -8.01
| ProductNoticesStore.View | p99 | 94ms | 90ms | -4ms | -4.26
| PostStore.AnalyticsPostCount | p99 | 995ms | 980ms | -15ms | -1.51
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 0s | 2ms | 2ms | 2752.28
| createUser | avg | 130ms | 283ms | 153ms | 117.33
| logout | avg | 27ms | 34ms | 7ms | 25.73
| createCategoryForTeamForUser | avg | 19ms | 23ms | 4ms | 21.56
| autocompleteChannelsForTeamForSearch | avg | 183ms | 209ms | 26ms | 14.23
| searchAllChannels | avg | 969ms | 989ms | 20ms | 2.06
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 88ms | 231ms | 143ms | 162.50
| createCategoryForTeamForUser | p99 | 25ms | 49ms | 24ms | 96.58
| unfollowThreadByUser | p99 | 25ms | 41ms | 16ms | 64.03
| createUser | p99 | 420ms | 497ms | 77ms | 18.34
| getPostsForChannelAroundLastUnread | p99 | 57ms | 64ms | 7ms | 12.27
| autocompleteUsers | p99 | 298ms | 326ms | 28ms | 9.39
| autocompleteChannelsForTeamForSearch | p99 | 2.225s | 2.306s | 81ms | 3.64
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 2ms | 0s | -2ms | -111.48
| updateChannelBookmarkSortOrder | avg | 14ms | 0s | -14ms | -103.29
| deleteChannelBookmark | avg | 16ms | 0s | -16ms | -97.34
| createEmoji | avg | 6ms | 0s | -6ms | -92.95
| listCPAFields | avg | 2ms | 0s | -2ms | -88.51
| updateReadStateAllThreadsByUser | avg | 6ms | 3ms | -3ms | -48.86
| createChannelBookmark | avg | 20ms | 13ms | -7ms | -35.47
| removeUserCustomStatus | avg | 113ms | 95ms | -18ms | -15.89
| createGroupChannel | avg | 264ms | 223ms | -41ms | -15.55
| createDirectChannel | avg | 173ms | 151ms | -22ms | -12.71
| getProfileImage | avg | 92ms | 81ms | -11ms | -11.92
| setPostReminder | avg | 19ms | 17ms | -2ms | -10.69
| searchPostsInTeam | avg | 72ms | 65ms | -7ms | -9.76
| updateCategoriesForTeamForUser | avg | 37ms | 34ms | -3ms | -8.09
| createChannel | avg | 199ms | 187ms | -12ms | -6.03
| createPost | avg | 236ms | 229ms | -7ms | -2.96
| addTeamMember | avg | 685ms | 674ms | -11ms | -1.61
| addChannelMember | avg | 160ms | 158ms | -2ms | -1.25
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAFields | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| createEmoji | p99 | 10ms | 0s | -10ms | -100.67
| updateChannelBookmarkSortOrder | p99 | 25ms | 0s | -25ms | -100.60
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| createSchedulePost | p99 | 43ms | 10ms | -33ms | -76.30
| createChannelBookmark | p99 | 94ms | 25ms | -69ms | -73.40
| getChannel | p99 | 35ms | 13ms | -22ms | -62.56
| searchPostsInTeam | p99 | 1.313s | 498ms | -815ms | -62.07
| updateCategoriesForTeamForUser | p99 | 214ms | 85ms | -129ms | -60.28
| setPostReminder | p99 | 47ms | 25ms | -22ms | -46.32
| deletePost | p99 | 44ms | 25ms | -19ms | -42.70
| upsertDraft | p99 | 16ms | 12ms | -4ms | -25.37
| getPostThread | p99 | 33ms | 25ms | -8ms | -24.14
| getChannelUnread | p99 | 10ms | 8ms | -2ms | -20.88
| getProfileImage | p99 | 454ms | 369ms | -85ms | -18.72
| patchPost | p99 | 80ms | 67ms | -13ms | -16.28
| viewChannel | p99 | 37ms | 31ms | -6ms | -16.17
| getUser | p99 | 12ms | 10ms | -2ms | -16.14
| addChannelMember | p99 | 455ms | 389ms | -66ms | -14.51
| updateReadStateThreadByUser | p99 | 58ms | 50ms | -8ms | -13.86
| getTeamScheduledPosts | p99 | 19ms | 17ms | -2ms | -10.59
| getChannelMember | p99 | 21ms | 19ms | -2ms | -9.57
| getFileThumbnail | p99 | 89ms | 87ms | -2ms | -2.25
| getPostsForChannel | p99 | 204ms | 200ms | -4ms | -1.96
| addTeamMember | p99 | 2.366s | 2.324s | -42ms | -1.78
| createChannel | p99 | 488ms | 480ms | -8ms | -1.64
| removeUserCustomStatus | p99 | 250ms | 246ms | -4ms | -1.60
| createDirectChannel | p99 | 468ms | 461ms | -7ms | -1.50
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.827
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -58.111
| ChannelBookmarkStore.Delete |  Avg| 6ms| 5ms | -1ms | -16.939
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.770
| ChannelBookmarkStore.Save |  Avg| 14ms| 8ms | -6ms | -43.959
| |  P99| 47ms| 24ms | -23ms | -49.200
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 5ms| 0s | -5ms | -94.707
| |  P99| 10ms| 0s | -10ms | -100.756
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.875
| ChannelStore.Autocomplete |  Avg| 969ms| 989ms | 20ms | 2.064
| |  P99| 2.459s| 2.46s | 1ms | 0.041
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 183ms| 209ms | 26ms | 14.237
| |  P99| 2.225s| 2.306s | 81ms | 3.640
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.472
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 16ms | -1ms | -6.018
| |  P99| 45ms| 44ms | -1ms | -2.207
| ChannelStore.CreateSidebarCategory |  Avg| 16ms| 18ms | 2ms | 12.688
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 3ms| 2ms | -1ms | -39.780
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.409
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 13ms | 2ms | 17.567
| |  P99| 70ms| 94ms | 24ms | 34.432
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -8.015
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.154
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.077
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.985
| ChannelStore.GetFileCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.879
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -23.467
| ChannelStore.GetMemberCount |  Avg| 76ms| 73ms | -3ms | -3.958
| |  P99| 247ms| 247ms | 0s | 0.000
| ChannelStore.GetMemberCountsByGroup |  Avg| 2ms| 0s | -2ms | -118.435
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.912
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.345
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 8ms| 7ms | -1ms | -13.269
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.610
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 11ms| 10ms | -1ms | -9.135
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 5ms | -1ms | -16.540
| |  P99| 76ms| 16ms | -60ms | -78.947
| ChannelStore.GetTeamChannels |  Avg| 30ms| 31ms | 1ms | 3.383
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.461
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 13ms| 12ms | -1ms | -7.458
| |  P99| 48ms| 47ms | -1ms | -2.077
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 67ms| 54ms | -13ms | -19.522
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.677
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -24.788
| ChannelStore.UpdateSidebarCategories |  Avg| 22ms| 23ms | 1ms | 4.560
| |  P99| 49ms| 85ms | 36ms | 74.227
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.475
| CommandWebhookStore.Cleanup |  Avg| 3ms| 1ms | -2ms | -79.918
| |  P99| 10ms| 5ms | -5ms | -51.020
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 0s | -1ms | -74.463
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.084
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 16ms| 13ms | -3ms | -19.224
| |  P99| 44ms| 25ms | -19ms | -42.697
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.174
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.518
| EmojiStore.GetMultipleByName |  Avg| 2ms| 3ms | 1ms | 45.629
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 11ms | -6ms | -35.210
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.574
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.444
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 4ms | -1ms | -21.658
| |  P99| 17ms| 13ms | -4ms | -23.140
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.725
| |  P99| 29ms| 22ms | -7ms | -23.796
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 3ms | 1ms | 40.669
| |  P99| 8ms| 9ms | 1ms | 11.847
| GroupStore.GetByName |  Avg| 3ms| 2ms | -1ms | -39.896
| |  P99| 10ms| 9ms | -1ms | -10.264
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.213
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 4ms| 2ms | -2ms | -53.360
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -40.207
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 40.816
| |  P99| 9ms| 59ms | 50ms | 575.816
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.231
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 32ms | 23ms | 263.862
| JobStore.UpdateOptimistically |  Avg| 4ms| 3ms | -1ms | -27.043
| |  P99| 13ms| 9ms | -4ms | -29.740
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 14.870
| JobStore.UpdateStatusOptimistically |  Avg| 7ms| 6ms | -1ms | -14.550
| |  P99| 19ms| 15ms | -4ms | -20.806
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.451
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 30.682
| |  P99| 9ms| 9ms | 0s | 0.000
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 17ms | -19ms | -53.521
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.253
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -36.585
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.216
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.526
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -42.683
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 788ms| 169ms | -619ms | -78.597
| |  P99| 995ms| 980ms | -15ms | -1.507
| PostStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 44ms| 25ms | -19ms | -42.697
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.434
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.716
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 2ms | -1ms | -39.503
| |  P99| 8ms| 7ms | -1ms | -13.136
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 6ms| 5ms | -1ms | -16.878
| |  P99| 24ms| 10ms | -14ms | -59.322
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.699
| PostStore.GetPostsAfter |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.792
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.441
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 9ms| 8ms | -1ms | -11.597
| |  P99| 47ms| 46ms | -1ms | -2.144
| PostStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 41ms| 37ms | -4ms | -9.663
| PostStore.SearchPostsForUser |  Avg| 66ms| 59ms | -7ms | -10.573
| |  P99| 1.313s| 461ms | -852ms | -64.884
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.317
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.504
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.058
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 1ms | -1ms | -63.111
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 26ms| 24ms | -2ms | -7.787
| |  P99| 94ms| 90ms | -4ms | -4.259
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 29.480
| |  P99| 10ms| 10ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 2ms | -1ms | -37.290
| |  P99| 38ms| 5ms | -33ms | -86.842
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 5ms| 3ms | -2ms | -41.517
| |  P99| 43ms| 9ms | -34ms | -78.612
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.653
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 1ms | -1ms | -64.963
| |  P99| 9ms| 5ms | -4ms | -46.512
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.533
| SessionStore.GetLRUSessions |  Avg| 2ms| 3ms | 1ms | 40.079
| |  P99| 8ms| 8ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.417
| SessionStore.Save |  Avg| 7ms| 6ms | -1ms | -15.310
| |  P99| 21ms| 19ms | -2ms | -9.641
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.471
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.649
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.464
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 205ms| 210ms | 5ms | 2.442
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -57.018
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -28.374
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.340
| TeamStore.GetActiveMemberCount |  Avg| 112ms| 112ms | 0s | 0.000
| |  P99| 249ms| 249ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.134
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.256
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.344
| TeamStore.GetTotalMemberCount |  Avg| 86ms| 88ms | 2ms | 2.314
| |  P99| 100ms| 238ms | 138ms | 138.693
| TeamStore.SaveMember |  Avg| 71ms| 70ms | -1ms | -1.413
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.332
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.457
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.785
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.646
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.898
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.660
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 2ms | -1ms | -39.918
| |  P99| 9ms| 8ms | -1ms | -11.739
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -23.351
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.383
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.776
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 3ms | -3ms | -49.797
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.361
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.467
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.454
| UserStore.AnalyticsActiveCount |  Avg| 157ms| 142ms | -15ms | -9.581
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 146ms| 147ms | 1ms | 0.684
| |  P99| 358ms| 381ms | 23ms | 6.429
| UserStore.Count |  Avg| 64ms| 80ms | 16ms | 24.884
| |  P99| 99ms| 232ms | 133ms | 133.983
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.341
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 259ms| 249ms | -10ms | -3.866
| |  P99| 498ms| 498ms | 0s | 0.000
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.557
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 41.072
| |  P99| 8ms| 20ms | 12ms | 151.903
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 3ms| 0s | -3ms | -86.564
| |  P99| 5ms| 0s | -5ms | -100.957
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -11.948
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.440
| UserStore.GetProfilesInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.243
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 28ms| 21ms | -7ms | -24.603
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 71ms | 1ms | 1.429
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 62ms| 63ms | 1ms | 1.613
| |  P99| 242ms| 242ms | 0s | 0.000
| UserStore.Update |  Avg| 5ms| 6ms | 1ms | 18.256
| |  P99| 10ms| 20ms | 10ms | 100.014
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 19.620
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 4ms | -1ms | -20.803
| |  P99| 34ms| 25ms | -9ms | -26.340
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 160ms| 158ms | -2ms | -1.246
| | P99| 455ms| 389ms | -66ms | -14.505
| addTeamMember | Avg| 685ms| 674ms | -11ms | -1.607
| | P99| 2.366s| 2.324s | -42ms | -1.775
| autocompleteChannelsForTeamForSearch | Avg| 183ms| 209ms | 26ms | 14.232
| | P99| 2.225s| 2.306s | 81ms | 3.640
| autocompleteUsers | Avg| 120ms| 120ms | 0s | 0.000
| | P99| 298ms| 326ms | 28ms | 9.388
| channelMemberCountsByGroup | Avg| 2ms| 0s | -2ms | -111.475
| | P99| 5ms| 0s | -5ms | -101.010
| createCategoryForTeamForUser | Avg| 19ms| 23ms | 4ms | 21.561
| | P99| 25ms| 49ms | 24ms | 96.579
| createChannel | Avg| 199ms| 187ms | -12ms | -6.030
| | P99| 488ms| 480ms | -8ms | -1.641
| createChannelBookmark | Avg| 20ms| 13ms | -7ms | -35.472
| | P99| 94ms| 25ms | -69ms | -73.404
| createDirectChannel | Avg| 173ms| 151ms | -22ms | -12.707
| | P99| 468ms| 461ms | -7ms | -1.495
| createEmoji | Avg| 6ms| 0s | -6ms | -92.946
| | P99| 10ms| 0s | -10ms | -100.671
| createGroupChannel | Avg| 264ms| 223ms | -41ms | -15.548
| | P99| 496ms| 494ms | -2ms | -0.403
| createPost | Avg| 236ms| 229ms | -7ms | -2.964
| | P99| 958ms| 955ms | -3ms | -0.313
| createSchedulePost | Avg| 5ms| 4ms | -1ms | -18.900
| | P99| 43ms| 10ms | -33ms | -76.300
| createUser | Avg| 130ms| 283ms | 153ms | 117.331
| | P99| 420ms| 497ms | 77ms | 18.340
| deleteChannelBookmark | Avg| 16ms| 0s | -16ms | -97.339
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 44ms| 25ms | -19ms | -42.697
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 11ms| 10ms | -1ms | -9.027
| getCategoriesForTeamForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 35ms| 13ms | -22ms | -62.559
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.567
| getChannelMembers | Avg| 4ms| 3ms | -1ms | -28.513
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.278
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 12ms | 0s | 0.000
| getChannelStats | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 220ms| 220ms | 0s | 0.000
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 8ms | -2ms | -20.884
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.005
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.400
| getClientConfig | Avg| 5ms| 4ms | -1ms | -21.825
| | P99| 19ms| 18ms | -1ms | -5.129
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getFilePreview | Avg| 39ms| 38ms | -1ms | -2.577
| | P99| 95ms| 94ms | -1ms | -1.051
| getFileThumbnail | Avg| 33ms| 32ms | -1ms | -3.074
| | P99| 89ms| 87ms | -2ms | -2.250
| getGroups | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 33ms| 25ms | -8ms | -24.137
| getPostsForChannel | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 204ms| 200ms | -4ms | -1.959
| getPostsForChannelAroundLastUnread | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 57ms| 64ms | 7ms | 12.266
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 12ms | 0s | 0.000
| getProfileImage | Avg| 92ms| 81ms | -11ms | -11.921
| | P99| 454ms| 369ms | -85ms | -18.717
| getPublicChannelsForTeam | Avg| 12ms| 11ms | -1ms | -8.407
| | P99| 25ms| 25ms | 0s | 0.000
| getRolesByNames | Avg| 0s| 2ms | 2ms | 2752.281
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 8ms | 1ms | 14.199
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 19ms| 17ms | -2ms | -10.590
| getTeamStats | Avg| 112ms| 112ms | 0s | 0.000
| | P99| 249ms| 249ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 10ms | -2ms | -16.139
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.351
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 2ms| 0s | -2ms | -88.510
| | P99| 5ms| 0s | -5ms | -101.010
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 68ms| 68ms | 0s | 0.000
| | P99| 245ms| 245ms | 0s | 0.000
| logout | Avg| 27ms| 34ms | 7ms | 25.728
| | P99| 88ms| 231ms | 143ms | 162.500
| patchPost | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 80ms| 67ms | -13ms | -16.276
| removeUserCustomStatus | Avg| 113ms| 95ms | -18ms | -15.885
| | P99| 250ms| 246ms | -4ms | -1.600
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 9ms | 1ms | 11.825
| | P99| 24ms| 24ms | 0s | 0.000
| searchAllChannels | Avg| 969ms| 989ms | 20ms | 2.063
| | P99| 2.459s| 2.46s | 1ms | 0.041
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -10.545
| searchPostsInTeam | Avg| 72ms| 65ms | -7ms | -9.758
| | P99| 1.313s| 498ms | -815ms | -62.066
| searchUsers | Avg| 63ms| 64ms | 1ms | 1.588
| | P99| 242ms| 242ms | 0s | 0.000
| setPostReminder | Avg| 19ms| 17ms | -2ms | -10.689
| | P99| 47ms| 25ms | -22ms | -46.316
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 41ms | 16ms | 64.031
| updateCategoriesForTeamForUser | Avg| 37ms| 34ms | -3ms | -8.090
| | P99| 214ms| 85ms | -129ms | -60.280
| updateChannelBookmarkSortOrder | Avg| 14ms| 0s | -14ms | -103.286
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 23ms| 22ms | -1ms | -4.417
| updateReadStateAllThreadsByUser | Avg| 6ms| 3ms | -3ms | -48.861
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 58ms| 50ms | -8ms | -13.860
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 427ms| 428ms | 1ms | 0.234
| | P99| 989ms| 993ms | 4ms | 0.404
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 16ms| 12ms | -4ms | -25.371
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 37ms| 31ms | -6ms | -16.171
