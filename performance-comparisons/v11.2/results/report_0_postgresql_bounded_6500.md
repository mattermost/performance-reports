### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.GetPendingScheduledPosts | avg | 2ms | 6ms | 4ms | 190.48
| PostStore.GetPostReminders | avg | 5ms | 7ms | 2ms | 37.25
| ChannelStore.CreateSidebarCategory | avg | 17ms | 22ms | 5ms | 30.25
| ChannelBookmarkStore.Save | avg | 8ms | 10ms | 2ms | 25.16
| PostStore.SearchPostsForUser | avg | 61ms | 73ms | 12ms | 19.71
| ChannelStore.Save | avg | 11ms | 13ms | 2ms | 18.61
| ChannelStore.UpdateSidebarCategories | avg | 36ms | 40ms | 4ms | 11.27
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 46ms | 41ms | 828.28
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 19ms | 14ms | 282.83
| UserStore.Update | p99 | 10ms | 36ms | 26ms | 261.27
| UserStore.GetByUsername | p99 | 7ms | 23ms | 16ms | 225.35
| ChannelBookmarkStore.Save | p99 | 10ms | 25ms | 15ms | 150.75
| PostStore.GetPostReminders | p99 | 10ms | 24ms | 14ms | 141.09
| RoleStore.ChannelHigherScopedPermissions | p99 | 9ms | 20ms | 11ms | 126.44
| JobStore.UpdateStatus | p99 | 9ms | 19ms | 10ms | 113.31
| PostStore.Update | p99 | 25ms | 51ms | 26ms | 104.65
| ChannelStore.GetTeamChannels | p99 | 25ms | 49ms | 24ms | 96.73
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 98ms | 48ms | 96.48
| BotStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.78
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 17ms | 7ms | 67.96
| FileInfoStore.GetByIds | p99 | 14ms | 22ms | 8ms | 58.61
| DraftStore.GetDraftsForUser | p99 | 9ms | 14ms | 5ms | 55.22
| ChannelStore.Save | p99 | 42ms | 62ms | 20ms | 47.76
| JobStore.GetAllByStatus | p99 | 17ms | 25ms | 8ms | 46.56
| ThreadStore.UpdateMembership | p99 | 6ms | 8ms | 2ms | 35.82
| ThreadStore.MarkAsRead | p99 | 6ms | 8ms | 2ms | 31.24
| EmojiStore.GetByName | p99 | 8ms | 10ms | 2ms | 23.88
| ThreadStore.GetTeamsUnreadForUser | p99 | 25ms | 29ms | 4ms | 16.08
| ChannelStore.GetMemberForPost | p99 | 14ms | 16ms | 2ms | 13.95
| ChannelStore.GetMember | p99 | 24ms | 27ms | 3ms | 12.38
| PostStore.GetPostsByThread | p99 | 20ms | 22ms | 2ms | 9.92
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 42ms | 46ms | 4ms | 9.64
| ChannelStore.SaveMember | p99 | 146ms | 160ms | 14ms | 9.60
| FileInfoStore.Save | p99 | 21ms | 23ms | 2ms | 9.45
| UserStore.GetProfileByIds | p99 | 21ms | 23ms | 2ms | 9.37
| TeamStore.SaveMember | p99 | 77ms | 84ms | 7ms | 9.06
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 22ms | 24ms | 2ms | 8.99
| TeamStore.GetMember | p99 | 22ms | 24ms | 2ms | 8.95
| ChannelStore.GetMembersForUserWithPagination | p99 | 26ms | 28ms | 2ms | 7.82
| PostStore.SearchPostsForUser | p99 | 832ms | 885ms | 53ms | 6.37
| UserStore.UpdateFailedPasswordAttempts | p99 | 32ms | 34ms | 2ms | 6.19
| UserStore.AutocompleteUsersInChannel | p99 | 157ms | 166ms | 9ms | 5.74
| ChannelStore.CreateInitialSidebarCategories | p99 | 88ms | 91ms | 3ms | 3.41
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | avg | 17ms | 0s | -17ms | -99.97
| PostStore.AnalyticsPostCount | avg | 497ms | 0s | -497ms | -99.91
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -95.21
| ScheduledPostStore.CreateScheduledPost | avg | 14ms | 3ms | -11ms | -78.11
| ChannelStore.AutocompleteInTeamForSearch | avg | 44ms | 38ms | -6ms | -13.63
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 0s | -25ms | -100.57
| PostStore.AnalyticsPostCount | p99 | 498ms | 0s | -498ms | -100.07
| ScheduledPostStore.CreateScheduledPost | p99 | 221ms | 9ms | -212ms | -95.71
| JobStore.GetCountByStatusAndType | p99 | 38ms | 9ms | -29ms | -76.82
| PostPriorityStore.GetForPost | p99 | 38ms | 9ms | -29ms | -76.33
| RoleStore.GetByNames | p99 | 23ms | 9ms | -14ms | -60.15
| ThreadStore.Get | p99 | 17ms | 7ms | -10ms | -57.29
| UserStore.GetMany | p99 | 20ms | 9ms | -11ms | -54.46
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 9ms | -9ms | -50.14
| ChannelStore.CreateDirectChannel | p99 | 95ms | 50ms | -45ms | -47.20
| ChannelStore.AutocompleteInTeamForSearch | p99 | 170ms | 98ms | -72ms | -42.23
| ClusterDiscoveryStore.SetLastPingAt | p99 | 19ms | 12ms | -7ms | -36.55
| ChannelStore.GetPublicChannelsForTeam | p99 | 39ms | 25ms | -14ms | -36.32
| ChannelStore.GetChannelUnread | p99 | 8ms | 5ms | -3ms | -35.72
| DraftStore.Delete | p99 | 9ms | 7ms | -2ms | -22.70
| FileInfoStore.SetContent | p99 | 46ms | 38ms | -8ms | -17.42
| StatusStore.UpdateLastActivityAt | p99 | 12ms | 10ms | -2ms | -17.37
| UserStore.GetUnreadCount | p99 | 14ms | 12ms | -2ms | -14.15
| DraftStore.Upsert | p99 | 15ms | 13ms | -2ms | -13.48
| UserStore.IsEmpty | p99 | 17ms | 15ms | -2ms | -11.99
| PreferenceStore.GetAll | p99 | 31ms | 29ms | -2ms | -6.56
| PreferenceStore.Save | p99 | 74ms | 72ms | -2ms | -2.72
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 91ms | 89ms | -2ms | -2.19
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 19ms | 29ms | 10ms | 51.53
| searchPostsInTeam | avg | 71ms | 83ms | 12ms | 17.00
| patchPost | avg | 26ms | 28ms | 2ms | 7.55
| updateCategoriesForTeamForUser | avg | 53ms | 57ms | 4ms | 7.49
| createChannel | avg | 169ms | 173ms | 4ms | 2.37
| uploadFileStream | avg | 392ms | 399ms | 7ms | 1.78
| createPost | avg | 160ms | 162ms | 2ms | 1.25
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 25ms | 50ms | 25ms | 100.60
| getTeamMember | p99 | 9ms | 17ms | 8ms | 87.36
| patchPost | p99 | 50ms | 76ms | 26ms | 52.36
| getChannel | p99 | 16ms | 24ms | 8ms | 49.31
| getDrafts | p99 | 10ms | 14ms | 4ms | 41.54
| listCPAFields | p99 | 25ms | 33ms | 8ms | 32.18
| saveReaction | p99 | 35ms | 40ms | 5ms | 14.36
| getAllTeams | p99 | 29ms | 33ms | 4ms | 13.66
| getChannelMembersForUser | p99 | 26ms | 29ms | 3ms | 11.46
| getCategoriesForTeamForUser | p99 | 44ms | 48ms | 4ms | 9.07
| autocompleteUsers | p99 | 124ms | 135ms | 11ms | 8.89
| getPostThread | p99 | 35ms | 38ms | 3ms | 8.51
| getUsers | p99 | 37ms | 40ms | 3ms | 8.16
| updateReadStateThreadByUser | p99 | 90ms | 97ms | 7ms | 7.74
| searchPostsInTeam | p99 | 832ms | 895ms | 63ms | 7.57
| getPostsForChannelAroundLastUnread | p99 | 110ms | 118ms | 8ms | 7.28
| getClientConfig | p99 | 59ms | 62ms | 3ms | 5.05
| getUser | p99 | 40ms | 42ms | 2ms | 5.00
| getTeamsUnreadForUser | p99 | 44ms | 46ms | 2ms | 4.55
| createPost | p99 | 787ms | 805ms | 18ms | 2.29
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -85.79
| createSchedulePost | avg | 15ms | 4ms | -11ms | -71.21
| followThreadByUser | avg | 14ms | 12ms | -2ms | -14.16
| autocompleteChannelsForTeamForSearch | avg | 44ms | 39ms | -5ms | -11.34
| addChannelMember | avg | 181ms | 167ms | -14ms | -7.72
| createDirectChannel | avg | 180ms | 171ms | -9ms | -4.99
| getProfileImage | avg | 88ms | 86ms | -2ms | -2.28
| createUser | avg | 213ms | 209ms | -4ms | -1.88
| login | avg | 119ms | 117ms | -2ms | -1.69
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -100.93
| createSchedulePost | p99 | 221ms | 10ms | -211ms | -95.26
| logout | p99 | 48ms | 25ms | -23ms | -47.54
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -42.25
| autocompleteChannelsForTeamForSearch | p99 | 170ms | 98ms | -72ms | -42.23
| getPublicChannelsForTeam | p99 | 39ms | 25ms | -14ms | -36.32
| addChannelMember | p99 | 468ms | 424ms | -44ms | -9.41
| createDirectChannel | p99 | 463ms | 422ms | -41ms | -8.85
| getChannelMember | p99 | 56ms | 53ms | -3ms | -5.32
| getProfileImage | p99 | 408ms | 387ms | -21ms | -5.14
| login | p99 | 626ms | 611ms | -15ms | -2.40
| getFileThumbnail | p99 | 86ms | 84ms | -2ms | -2.33
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 47.754
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 8ms| 10ms | 2ms | 25.164
| |  P99| 10ms| 25ms | 15ms | 150.754
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 44ms| 38ms | -6ms | -13.627
| |  P99| 170ms| 98ms | -72ms | -42.230
| ChannelStore.CreateDirectChannel |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 95ms| 50ms | -45ms | -47.201
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 88ms| 91ms | 3ms | 3.407
| ChannelStore.CreateSidebarCategory |  Avg| 17ms| 22ms | 5ms | 30.250
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 15ms | 1ms | 6.906
| |  P99| 91ms| 89ms | -2ms | -2.193
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 42ms| 43ms | 1ms | 2.409
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.715
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.463
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.259
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 33ms | 1ms | 3.140
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.376
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 48ms| 49ms | 1ms | 2.063
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 13.948
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -95.208
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.106
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 26ms| 28ms | 2ms | 7.816
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.252
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -36.323
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 42ms| 46ms | 4ms | 9.636
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 13ms| 14ms | 1ms | 7.942
| |  P99| 25ms| 49ms | 24ms | 96.725
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.Save |  Avg| 11ms| 13ms | 2ms | 18.615
| |  P99| 42ms| 62ms | 20ms | 47.761
| ChannelStore.SaveMember |  Avg| 32ms| 31ms | -1ms | -3.165
| |  P99| 146ms| 160ms | 14ms | 9.603
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.951
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.050
| ChannelStore.UpdateSidebarCategories |  Avg| 36ms| 40ms | 4ms | 11.266
| |  P99| 50ms| 98ms | 48ms | 96.482
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 12ms | -7ms | -36.550
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.700
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 14ms | 5ms | 55.221
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.478
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.879
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 7ms | 1ms | 15.842
| |  P99| 23ms| 24ms | 1ms | 4.271
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.003
| FileInfoStore.GetByIds |  Avg| 2ms| 3ms | 1ms | 40.541
| |  P99| 14ms| 22ms | 8ms | 58.606
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.878
| FileInfoStore.Save |  Avg| 4ms| 5ms | 1ms | 22.286
| |  P99| 21ms| 23ms | 2ms | 9.454
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 38ms | -8ms | -17.423
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.989
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.809
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.121
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 25ms | 8ms | 46.562
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -38.902
| |  P99| 38ms| 9ms | -29ms | -76.821
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 3ms | 1ms | 44.537
| |  P99| 10ms| 17ms | 7ms | 67.961
| JobStore.Save |  Avg| 3ms| 4ms | 1ms | 31.613
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.072
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 113.314
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -50.139
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.962
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 9ms | -29ms | -76.327
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 497ms| 0s | -497ms | -99.913
| |  P99| 498ms| 0s | -498ms | -100.071
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 5ms| 7ms | 2ms | 37.254
| |  P99| 10ms| 24ms | 14ms | 141.090
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.047
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.782
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.301
| PostStore.GetPostsByThread |  Avg| 5ms| 6ms | 1ms | 19.040
| |  P99| 20ms| 22ms | 2ms | 9.923
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.318
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 61ms| 73ms | 12ms | 19.709
| |  P99| 832ms| 885ms | 53ms | 6.372
| PostStore.SetPostReminder |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 12ms| 13ms | 1ms | 8.086
| |  P99| 25ms| 51ms | 26ms | 104.649
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 31ms| 29ms | -2ms | -6.556
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 74ms| 72ms | -2ms | -2.715
| ProductNoticesStore.ClearOldNotices |  Avg| 17ms| 0s | -17ms | -99.970
| |  P99| 25ms| 0s | -25ms | -100.568
| ProductNoticesStore.View |  Avg| 42ms| 41ms | -1ms | -2.381
| |  P99| 214ms| 212ms | -2ms | -0.937
| PropertyFieldStore.SearchPropertyFields |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.197
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 3ms | 1ms | 41.981
| |  P99| 14ms| 14ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.721
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 126.437
| RoleStore.GetByNames |  Avg| 4ms| 3ms | -1ms | -28.565
| |  P99| 23ms| 9ms | -14ms | -60.150
| ScheduledPostStore.CreateScheduledPost |  Avg| 14ms| 3ms | -11ms | -78.108
| |  P99| 221ms| 9ms | -212ms | -95.713
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 6ms | 4ms | 190.481
| |  P99| 5ms| 46ms | 41ms | 828.283
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.221
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.145
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.674
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.553
| StatusStore.SaveOrUpdateMany |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.375
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.975
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.091
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.952
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.108
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 23ms | 1ms | 4.453
| |  P99| 77ms| 84ms | 7ms | 9.063
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 7ms | -10ms | -57.290
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.083
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.324
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.574
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.433
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.237
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 35.823
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 157ms| 166ms | 9ms | 5.743
| UserStore.Count |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.019
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.168
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.441
| UserStore.GetAllProfilesInChannel |  Avg| 161ms| 162ms | 1ms | 0.622
| |  P99| 482ms| 483ms | 1ms | 0.207
| UserStore.GetByUsername |  Avg| 2ms| 3ms | 1ms | 41.498
| |  P99| 7ms| 23ms | 16ms | 225.351
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetMany |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 9ms | -11ms | -54.458
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 23ms | 2ms | 9.367
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 22.651
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.148
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.988
| UserStore.Save |  Avg| 139ms| 138ms | -1ms | -0.717
| |  P99| 250ms| 249ms | -1ms | -0.400
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 36ms | 26ms | 261.267
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 32ms| 34ms | 2ms | 6.187
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.162
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.047
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 181ms| 167ms | -14ms | -7.721
| | P99| 468ms| 424ms | -44ms | -9.412
| addTeamMember | Avg| 663ms| 663ms | 0s | 0.000
| | P99| 2.325s| 2.324s | -1ms | -0.043
| autocompleteChannelsForTeamForSearch | Avg| 44ms| 39ms | -5ms | -11.339
| | P99| 170ms| 98ms | -72ms | -42.230
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 124ms| 135ms | 11ms | 8.891
| createCategoryForTeamForUser | Avg| 19ms| 29ms | 10ms | 51.531
| | P99| 25ms| 50ms | 25ms | 100.604
| createChannel | Avg| 169ms| 173ms | 4ms | 2.370
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 14ms| 15ms | 1ms | 7.086
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 180ms| 171ms | -9ms | -4.995
| | P99| 463ms| 422ms | -41ms | -8.847
| createGroupChannel | Avg| 265ms| 265ms | 0s | 0.000
| | P99| 496ms| 496ms | 0s | 0.000
| createPost | Avg| 160ms| 162ms | 2ms | 1.248
| | P99| 787ms| 805ms | 18ms | 2.287
| createSchedulePost | Avg| 15ms| 4ms | -11ms | -71.214
| | P99| 221ms| 10ms | -211ms | -95.262
| createUser | Avg| 213ms| 209ms | -4ms | -1.882
| | P99| 494ms| 491ms | -3ms | -0.607
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.464
| deletePost | Avg| 23ms| 24ms | 1ms | 4.333
| | P99| 49ms| 49ms | 0s | 0.000
| followThreadByUser | Avg| 14ms| 12ms | -2ms | -14.160
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 29ms| 33ms | 4ms | 13.658
| getCategoriesForTeamForUser | Avg| 7ms| 8ms | 1ms | 13.645
| | P99| 44ms| 48ms | 4ms | 9.073
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 16ms| 24ms | 8ms | 49.310
| getChannelMember | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 56ms| 53ms | -3ms | -5.323
| getChannelMembers | Avg| 3ms| 0s | -3ms | -85.787
| | P99| 5ms| 0s | -5ms | -100.931
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.066
| getChannelMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 26ms| 29ms | 3ms | 11.457
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 36ms| 36ms | 0s | 0.000
| getChannelUnread | Avg| 3ms| 2ms | -1ms | -34.503
| | P99| 9ms| 5ms | -4ms | -42.253
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getChannelsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.241
| getClientConfig | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 59ms| 62ms | 3ms | 5.054
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 14ms | 4ms | 41.543
| getFilePreview | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 92ms| 92ms | 0s | 0.000
| getFileThumbnail | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 86ms| 84ms | -2ms | -2.334
| getPostThread | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 35ms| 38ms | 3ms | 8.512
| getPostsForChannel | Avg| 23ms| 23ms | 0s | 0.000
| | P99| 194ms| 193ms | -1ms | -0.516
| getPostsForChannelAroundLastUnread | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 110ms| 118ms | 8ms | 7.278
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 32ms| 32ms | 0s | 0.000
| getProfileImage | Avg| 88ms| 86ms | -2ms | -2.283
| | P99| 408ms| 387ms | -21ms | -5.143
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 39ms| 25ms | -14ms | -36.323
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 17ms | 8ms | 87.360
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 30ms| 30ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 6ms| 7ms | 1ms | 15.671
| | P99| 46ms| 47ms | 1ms | 2.194
| getTeamStats | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 25ms | 1ms | 4.087
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 44ms| 46ms | 2ms | 4.553
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.066
| getUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 40ms| 42ms | 2ms | 4.999
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 5ms | 1ms | 22.731
| | P99| 37ms| 40ms | 3ms | 8.157
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 4ms | 1ms | 28.977
| | P99| 25ms| 33ms | 8ms | 32.177
| listCPAValues | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 13ms | 0s | 0.000
| login | Avg| 119ms| 117ms | -2ms | -1.686
| | P99| 626ms| 611ms | -15ms | -2.396
| logout | Avg| 23ms| 22ms | -1ms | -4.294
| | P99| 48ms| 25ms | -23ms | -47.543
| patchPost | Avg| 26ms| 28ms | 2ms | 7.552
| | P99| 50ms| 76ms | 26ms | 52.362
| removeUserCustomStatus | Avg| 110ms| 109ms | -1ms | -0.912
| | P99| 247ms| 248ms | 1ms | 0.405
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 35ms| 40ms | 5ms | 14.363
| searchAllChannels | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.769
| searchPostsInTeam | Avg| 71ms| 83ms | 12ms | 16.996
| | P99| 832ms| 895ms | 63ms | 7.574
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 53ms| 57ms | 4ms | 7.494
| | P99| 99ms| 99ms | 0s | 0.000
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 38ms| 39ms | 1ms | 2.639
| | P99| 90ms| 97ms | 7ms | 7.739
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 392ms| 399ms | 7ms | 1.785
| | P99| 983ms| 988ms | 5ms | 0.508
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 18ms| 17ms | -1ms | -5.512
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 40ms| 40ms | 0s | 0.000
