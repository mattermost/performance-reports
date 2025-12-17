### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 26ms | 37ms | 11ms | 42.49
| ChannelStore.GetSidebarCategory | avg | 5ms | 7ms | 2ms | 41.57
| ChannelBookmarkStore.Save | avg | 5ms | 7ms | 2ms | 39.24
| UserStore.GetProfilesInChannel | avg | 9ms | 12ms | 3ms | 32.79
| ChannelStore.UpdateSidebarCategories | avg | 17ms | 22ms | 5ms | 30.19
| ChannelStore.GetTeamChannels | avg | 10ms | 12ms | 2ms | 20.86
| TeamStore.GetActiveMemberCount | avg | 33ms | 38ms | 5ms | 15.21
| PostStore.SearchPostsForUser | avg | 67ms | 72ms | 5ms | 7.42
| UserStore.Save | avg | 127ms | 129ms | 2ms | 1.58
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 21ms | 16ms | 323.21
| ChannelStore.UpdateSidebarCategories | p99 | 25ms | 91ms | 66ms | 265.59
| JobStore.GetNewestJobByStatusesAndType | p99 | 18ms | 50ms | 32ms | 181.30
| ChannelStore.CreateSidebarCategory | p99 | 10ms | 25ms | 15ms | 150.75
| ChannelStore.GetSidebarCategory | p99 | 10ms | 24ms | 14ms | 141.41
| ClusterDiscoveryStore.SetLastPingAt | p99 | 5ms | 12ms | 7ms | 140.62
| FileInfoStore.GetByIds | p99 | 6ms | 14ms | 8ms | 135.98
| ChannelStore.Save | p99 | 32ms | 71ms | 39ms | 120.93
| FileInfoStore.Save | p99 | 10ms | 21ms | 11ms | 113.28
| UserStore.Update | p99 | 18ms | 37ms | 19ms | 104.97
| UserStore.GetByUsername | p99 | 5ms | 10ms | 5ms | 101.01
| BotStore.Get | p99 | 5ms | 10ms | 5ms | 101.01
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 100.98
| TeamStore.GetActiveMemberCount | p99 | 50ms | 97ms | 47ms | 94.47
| PostPersistentNotificationStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetChannelUnread | p99 | 5ms | 8ms | 3ms | 60.61
| PostPriorityStore.GetForPost | p99 | 5ms | 7ms | 2ms | 40.16
| PostStore.GetPostsByThread | p99 | 10ms | 14ms | 4ms | 40.07
| ThreadStore.MaintainMembership | p99 | 10ms | 14ms | 4ms | 39.99
| ChannelStore.AutocompleteInTeamForSearch | p99 | 71ms | 99ms | 28ms | 39.44
| ChannelStore.CreateInitialSidebarCategories | p99 | 53ms | 66ms | 13ms | 24.42
| UserStore.IsEmpty | p99 | 12ms | 15ms | 3ms | 24.07
| ChannelStore.IncrementMentionCount | p99 | 16ms | 19ms | 3ms | 18.27
| ChannelStore.GetGuestCount | p99 | 25ms | 29ms | 4ms | 16.18
| ProductNoticesStore.View | p99 | 140ms | 161ms | 21ms | 14.98
| PreferenceStore.Save | p99 | 49ms | 56ms | 7ms | 14.19
| JobStore.GetCountByStatusAndType | p99 | 38ms | 43ms | 5ms | 13.25
| PostStore.Save | p99 | 33ms | 36ms | 3ms | 9.22
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 33ms | 36ms | 3ms | 9.21
| SessionStore.Save | p99 | 33ms | 36ms | 3ms | 8.98
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 264ms | 2ms | -262ms | -99.14
| ProductNoticesStore.ClearOldNotices | avg | 16ms | 0s | -16ms | -97.90
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -96.52
| ChannelBookmarkStore.Delete | avg | 3ms | 0s | -3ms | -87.08
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 4ms | 2ms | -2ms | -50.89
| StatusStore.SaveOrUpdateMany | avg | 6ms | 4ms | -2ms | -32.02
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 0s | -25ms | -100.60
| PostStore.AnalyticsPostCount | p99 | 497ms | 5ms | -492ms | -98.89
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 45ms | 5ms | -40ms | -87.91
| UserAccessTokenStore.GetByToken | p99 | 23ms | 5ms | -18ms | -78.60
| StatusStore.SaveOrUpdateMany | p99 | 43ms | 10ms | -33ms | -77.65
| JobStore.UpdateOptimistically | p99 | 18ms | 5ms | -13ms | -72.42
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 24ms | 9ms | -15ms | -62.63
| PostStore.Delete | p99 | 24ms | 10ms | -14ms | -58.44
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 8ms | -10ms | -55.24
| UserStore.GetMany | p99 | 43ms | 20ms | -23ms | -53.49
| PreferenceStore.DeleteCategoryAndName | p99 | 10ms | 5ms | -5ms | -51.82
| PostStore.SetPostReminder | p99 | 10ms | 5ms | -5ms | -50.89
| JobStore.Save | p99 | 38ms | 19ms | -19ms | -49.67
| FileInfoStore.SetContent | p99 | 16ms | 9ms | -7ms | -44.80
| ChannelStore.CreateDirectChannel | p99 | 42ms | 25ms | -17ms | -40.30
| FileInfoStore.AttachToPost | p99 | 24ms | 16ms | -8ms | -33.52
| PostStore.GetPostIdAfterTime | p99 | 18ms | 13ms | -5ms | -28.39
| JobStore.GetAllByStatus | p99 | 16ms | 12ms | -4ms | -24.93
| ReactionStore.GetForPost | p99 | 8ms | 6ms | -2ms | -24.27
| ChannelStore.SearchGroupChannels | p99 | 17ms | 13ms | -4ms | -23.43
| ThreadStore.GetThreadsForUser | p99 | 13ms | 11ms | -2ms | -15.53
| UserStore.AutocompleteUsersInChannel | p99 | 176ms | 167ms | -9ms | -5.13
| SessionStore.Get | p99 | 43ms | 41ms | -2ms | -4.61
| TeamStore.SaveMember | p99 | 59ms | 57ms | -2ms | -3.40
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 26ms | 37ms | 11ms | 42.37
| updateCategoriesForTeamForUser | avg | 28ms | 37ms | 9ms | 32.00
| createCategoryForTeamForUser | avg | 11ms | 13ms | 2ms | 18.98
| getTeamStats | avg | 33ms | 38ms | 5ms | 15.16
| removeUserCustomStatus | avg | 102ms | 112ms | 10ms | 9.77
| createChannel | avg | 146ms | 156ms | 10ms | 6.86
| searchPostsInTeam | avg | 73ms | 77ms | 4ms | 5.52
| login | avg | 97ms | 101ms | 4ms | 4.10
| createUser | avg | 184ms | 188ms | 4ms | 2.18
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 50ms | 97ms | 47ms | 94.47
| updateCategoriesForTeamForUser | p99 | 50ms | 91ms | 41ms | 82.46
| getChannelUnread | p99 | 5ms | 8ms | 3ms | 60.61
| autocompleteChannelsForTeamForSearch | p99 | 71ms | 99ms | 28ms | 39.44
| patchPost | p99 | 37ms | 50ms | 13ms | 35.26
| listCPAValues | p99 | 6ms | 8ms | 2ms | 32.48
| upsertDraft | p99 | 12ms | 14ms | 2ms | 17.30
| unfollowThreadByUser | p99 | 17ms | 19ms | 2ms | 11.53
| getPublicChannelsForTeam | p99 | 25ms | 27ms | 2ms | 8.00
| getChannelStats | p99 | 26ms | 28ms | 2ms | 7.84
| saveReaction | p99 | 26ms | 28ms | 2ms | 7.55
| getCategoriesForTeamForUser | p99 | 36ms | 38ms | 2ms | 5.60
| addTeamMember | p99 | 2.155s | 2.189s | 34ms | 1.58
| login | p99 | 487ms | 494ms | 7ms | 1.44
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | avg | 14ms | 0s | -14ms | -102.70
| getChannelMembers | avg | 4ms | 0s | -4ms | -102.39
| createDirectChannel | avg | 162ms | 146ms | -16ms | -9.88
| createGroupChannel | avg | 249ms | 229ms | -20ms | -8.05
| addChannelMember | avg | 153ms | 148ms | -5ms | -3.27
| getProfileImage | avg | 95ms | 92ms | -3ms | -3.14
| uploadFileStream | avg | 432ms | 426ms | -6ms | -1.39
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| createSchedulePost | p99 | 43ms | 9ms | -34ms | -79.44
| logout | p99 | 48ms | 25ms | -23ms | -48.10
| getChannel | p99 | 9ms | 5ms | -4ms | -43.48
| createDirectChannel | p99 | 354ms | 248ms | -106ms | -29.96
| searchGroupChannels | p99 | 18ms | 13ms | -5ms | -28.46
| getChannelsForUser | p99 | 25ms | 23ms | -2ms | -8.16
| autocompleteUsers | p99 | 156ms | 146ms | -10ms | -6.40
| getProfileImage | p99 | 474ms | 458ms | -16ms | -3.38
| getPostsForChannel | p99 | 98ms | 95ms | -3ms | -3.07
| createPost | p99 | 698ms | 682ms | -16ms | -2.29
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| ChannelBookmarkStore.Delete |  Avg| 3ms| 0s | -3ms | -87.081
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Get |  Avg| 1ms| 0s | -1ms | -71.065
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 5ms| 7ms | 2ms | 39.244
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.168
| ChannelStore.Autocomplete |  Avg| 30ms| 31ms | 1ms | 3.324
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 26ms| 37ms | 11ms | 42.485
| |  P99| 71ms| 99ms | 28ms | 39.440
| ChannelStore.CreateDirectChannel |  Avg| 13ms| 12ms | -1ms | -7.622
| |  P99| 42ms| 25ms | -17ms | -40.296
| ChannelStore.CreateInitialSidebarCategories |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 53ms| 66ms | 13ms | 24.424
| ChannelStore.CreateSidebarCategory |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 10ms| 25ms | 15ms | 150.754
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 84ms| 85ms | 1ms | 1.186
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 2ms | 1ms | 83.419
| |  P99| 5ms| 8ms | 3ms | 60.606
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.320
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.138
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.179
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.826
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.865
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -96.523
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 9.214
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 7ms | 2ms | 41.568
| |  P99| 10ms| 24ms | 14ms | 141.414
| ChannelStore.GetTeamChannels |  Avg| 10ms| 12ms | 2ms | 20.861
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.274
| ChannelStore.Save |  Avg| 7ms| 8ms | 1ms | 14.045
| |  P99| 32ms| 71ms | 39ms | 120.933
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 13ms | -4ms | -23.432
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 17ms| 22ms | 5ms | 30.188
| |  P99| 25ms| 91ms | 66ms | 265.594
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 12ms | 7ms | 140.620
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 2ms | -2ms | -50.894
| |  P99| 24ms| 9ms | -15ms | -62.633
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.294
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.519
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 16ms | -8ms | -33.519
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 2ms | 1ms | 72.707
| |  P99| 6ms| 14ms | 8ms | 135.976
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 113.277
| FileInfoStore.SetContent |  Avg| 5ms| 4ms | -1ms | -20.508
| |  P99| 16ms| 9ms | -7ms | -44.798
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.505
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 6.905
| JobStore.GetAllByStatus |  Avg| 2ms| 1ms | -1ms | -61.266
| |  P99| 16ms| 12ms | -4ms | -24.933
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 43ms | 5ms | 13.245
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 50ms | 32ms | 181.303
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -27.860
| |  P99| 38ms| 19ms | -19ms | -49.673
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.423
| JobStore.UpdateStatus |  Avg| 2ms| 3ms | 1ms | 40.165
| |  P99| 18ms| 19ms | 1ms | 5.571
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -55.244
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.162
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 264ms| 2ms | -262ms | -99.141
| |  P99| 497ms| 5ms | -492ms | -98.894
| PostStore.Delete |  Avg| 9ms| 8ms | -1ms | -11.531
| |  P99| 24ms| 10ms | -14ms | -58.442
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -28.387
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 9.673
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.068
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.409
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 8ms | 1ms | 13.407
| |  P99| 33ms| 36ms | 3ms | 9.218
| PostStore.SearchPostsForUser |  Avg| 67ms| 72ms | 5ms | 7.423
| |  P99| 901ms| 895ms | -6ms | -0.666
| PostStore.SetPostReminder |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.890
| PostStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.087
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 1ms | -1ms | -55.476
| |  P99| 10ms| 5ms | -5ms | -51.815
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 6ms| 7ms | 1ms | 15.785
| |  P99| 49ms| 56ms | 7ms | 14.185
| ProductNoticesStore.ClearOldNotices |  Avg| 16ms| 0s | -16ms | -97.895
| |  P99| 25ms| 0s | -25ms | -100.602
| ProductNoticesStore.View |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 140ms| 161ms | 21ms | 14.976
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.298
| PropertyValueStore.SearchPropertyValues |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.212
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.266
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 3ms | 1ms | 41.639
| |  P99| 5ms| 21ms | 16ms | 323.208
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 1ms | -1ms | -42.910
| |  P99| 45ms| 5ms | -40ms | -87.912
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.605
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 1ms | -1ms | -66.304
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.978
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 8.981
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.152
| StatusStore.SaveOrUpdateMany |  Avg| 6ms| 4ms | -2ms | -32.021
| |  P99| 43ms| 10ms | -33ms | -77.647
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.632
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.111
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 33ms| 38ms | 5ms | 15.208
| |  P99| 50ms| 97ms | 47ms | 94.472
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -5.108
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.467
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 17ms| 18ms | 1ms | 5.737
| |  P99| 59ms| 57ms | -2ms | -3.402
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.419
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.289
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.530
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.893
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 39.989
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 2ms | 1ms | 70.163
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -51.908
| |  P99| 23ms| 5ms | -18ms | -78.602
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 176ms| 167ms | -9ms | -5.125
| UserStore.Count |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 150ms| 150ms | 0s | 0.000
| |  P99| 475ms| 476ms | 1ms | 0.210
| UserStore.GetByUsername |  Avg| 1ms| 2ms | 1ms | 70.609
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.GetMany |  Avg| 3ms| 2ms | -1ms | -33.515
| |  P99| 43ms| 20ms | -23ms | -53.489
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 9ms| 12ms | 3ms | 32.792
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 24.066
| UserStore.Save |  Avg| 127ms| 129ms | 2ms | 1.580
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.014
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 37ms | 19ms | 104.969
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.107
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.486
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 153ms| 148ms | -5ms | -3.274
| | P99| 248ms| 250ms | 2ms | 0.805
| addTeamMember | Avg| 575ms| 579ms | 4ms | 0.696
| | P99| 2.155s| 2.189s | 34ms | 1.578
| autocompleteChannelsForTeamForSearch | Avg| 26ms| 37ms | 11ms | 42.368
| | P99| 71ms| 99ms | 28ms | 39.440
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 156ms| 146ms | -10ms | -6.401
| createCategoryForTeamForUser | Avg| 11ms| 13ms | 2ms | 18.982
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 146ms| 156ms | 10ms | 6.862
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 11ms| 12ms | 1ms | 9.098
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 162ms| 146ms | -16ms | -9.882
| | P99| 354ms| 248ms | -106ms | -29.964
| createGroupChannel | Avg| 249ms| 229ms | -20ms | -8.048
| | P99| 496ms| 493ms | -3ms | -0.605
| createPost | Avg| 140ms| 139ms | -1ms | -0.714
| | P99| 698ms| 682ms | -16ms | -2.292
| createSchedulePost | Avg| 4ms| 3ms | -1ms | -26.432
| | P99| 43ms| 9ms | -34ms | -79.440
| createUser | Avg| 184ms| 188ms | 4ms | 2.179
| | P99| 484ms| 485ms | 1ms | 0.207
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 36ms| 38ms | 2ms | 5.597
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -43.479
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 44ms| 45ms | 1ms | 2.249
| getChannelMembers | Avg| 4ms| 0s | -4ms | -102.386
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -5.976
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 26ms| 28ms | 2ms | 7.843
| getChannelUnread | Avg| 1ms| 2ms | 1ms | 77.854
| | P99| 5ms| 8ms | 3ms | 60.606
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 15ms | 1ms | 7.278
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 23ms | -2ms | -8.161
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 44ms| 45ms | 1ms | 2.268
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.294
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 93ms| 94ms | 1ms | 1.071
| getFileThumbnail | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 90ms| 90ms | 0s | 0.000
| getPostThread | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 15ms| 14ms | -1ms | -6.716
| | P99| 98ms| 95ms | -3ms | -3.066
| getPostsForChannelAroundLastUnread | Avg| 12ms| 13ms | 1ms | 8.021
| | P99| 88ms| 89ms | 1ms | 1.141
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getProfileImage | Avg| 95ms| 92ms | -3ms | -3.144
| | P99| 474ms| 458ms | -16ms | -3.377
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 27ms | 2ms | 8.004
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 37ms| 36ms | -1ms | -2.739
| getTeamStats | Avg| 33ms| 38ms | 5ms | 15.160
| | P99| 50ms| 97ms | 47ms | 94.472
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 37ms | -1ms | -2.610
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 36ms| 37ms | 1ms | 2.747
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 32ms | 1ms | 3.185
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.090
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| listCPAValues | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 8ms | 2ms | 32.476
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 97ms| 101ms | 4ms | 4.104
| | P99| 487ms| 494ms | 7ms | 1.438
| logout | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 48ms| 25ms | -23ms | -48.097
| patchPost | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 37ms| 50ms | 13ms | 35.256
| removeUserCustomStatus | Avg| 102ms| 112ms | 10ms | 9.775
| | P99| 246ms| 247ms | 1ms | 0.406
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 26ms| 28ms | 2ms | 7.547
| searchAllChannels | Avg| 30ms| 31ms | 1ms | 3.302
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 13ms | -5ms | -28.464
| searchPostsInTeam | Avg| 73ms| 77ms | 4ms | 5.515
| | P99| 901ms| 904ms | 3ms | 0.333
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 17ms| 19ms | 2ms | 11.528
| updateCategoriesForTeamForUser | Avg| 28ms| 37ms | 9ms | 31.995
| | P99| 50ms| 91ms | 41ms | 82.456
| updateChannelBookmark | Avg| 14ms| 0s | -14ms | -102.704
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 432ms| 426ms | -6ms | -1.388
| | P99| 990ms| 992ms | 2ms | 0.202
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 14ms | 2ms | 17.303
| viewChannel | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 26ms| 27ms | 1ms | 3.819
