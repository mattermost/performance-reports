### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 4ms | 20ms | 16ms | 402.92
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 15ms | 17ms | 2ms | 13.74
| PostStore.SearchPostsForUser | avg | 81ms | 83ms | 2ms | 2.48
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 18ms | 295ms | 277ms | 1527.59
| JobStore.UpdateStatus | p99 | 5ms | 38ms | 33ms | 666.67
| LinkMetadataStore.Save | p99 | 5ms | 24ms | 19ms | 383.84
| FileInfoStore.GetByIds | p99 | 5ms | 13ms | 8ms | 160.28
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| PostStore.GetPostReminders | p99 | 10ms | 22ms | 12ms | 120.60
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 51ms | 26ms | 104.61
| JobStore.Save | p99 | 5ms | 9ms | 4ms | 80.81
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 9ms | 4ms | 80.79
| JobStore.UpdateOptimistically | p99 | 5ms | 8ms | 3ms | 60.61
| ClusterDiscoveryStore.SetLastPingAt | p99 | 22ms | 31ms | 9ms | 40.77
| ChannelStore.CreateDirectChannel | p99 | 50ms | 68ms | 18ms | 36.28
| ChannelStore.GetPinnedPostCount | p99 | 7ms | 9ms | 2ms | 26.93
| DraftStore.GetDraftsForUser | p99 | 13ms | 16ms | 3ms | 22.53
| PostStore.Get | p99 | 22ms | 24ms | 2ms | 8.99
| ChannelStore.Save | p99 | 32ms | 34ms | 2ms | 6.30
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 156ms | 165ms | 9ms | 5.77
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 34ms | 0s | -34ms | -98.68
| PostStore.AnalyticsPostCount | avg | 506ms | 260ms | -246ms | -48.58
| TeamStore.GetTotalMemberCount | avg | 36ms | 19ms | -17ms | -47.71
| ChannelStore.GetSidebarCategory | avg | 8ms | 6ms | -2ms | -24.04
| ChannelStore.AutocompleteInTeamForSearch | avg | 36ms | 30ms | -6ms | -16.87
| ChannelStore.UpdateSidebarCategories | avg | 45ms | 39ms | -6ms | -13.45
| PostStore.Delete | avg | 16ms | 14ms | -2ms | -12.34
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | p99 | 50ms | 0s | -50ms | -100.50
| UserStore.GetByUsername | p99 | 21ms | 5ms | -16ms | -76.30
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 22ms | 5ms | -17ms | -76.23
| ChannelStore.GetSidebarCategory | p99 | 25ms | 10ms | -15ms | -61.08
| PluginStore.List | p99 | 20ms | 9ms | -11ms | -56.12
| JobStore.UpdateStatusOptimistically | p99 | 18ms | 8ms | -10ms | -55.71
| TeamStore.GetTotalMemberCount | p99 | 50ms | 25ms | -25ms | -50.25
| PostStore.AnalyticsPostCount | p99 | 995ms | 498ms | -497ms | -49.95
| PostPriorityStore.GetForPost | p99 | 12ms | 6ms | -6ms | -49.59
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -44.45
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -44.41
| ChannelStore.AutocompleteInTeamForSearch | p99 | 175ms | 98ms | -77ms | -43.99
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 5ms | -4ms | -43.96
| ChannelStore.UpdateSidebarCategories | p99 | 88ms | 50ms | -38ms | -43.39
| RoleStore.ChannelHigherScopedPermissions | p99 | 9ms | 5ms | -4ms | -43.26
| PostAcknowledgementStore.GetForPost | p99 | 14ms | 8ms | -6ms | -42.25
| StatusStore.UpdateExpiredDNDStatuses | p99 | 20ms | 12ms | -8ms | -39.02
| FileInfoStore.Get | p99 | 7ms | 5ms | -2ms | -29.73
| ReactionStore.GetForPost | p99 | 14ms | 10ms | -4ms | -29.50
| PostPersistentNotificationStore.GetSingle | p99 | 7ms | 5ms | -2ms | -27.91
| UserStore.GetAllProfiles | p99 | 19ms | 14ms | -5ms | -26.99
| UserStore.IsEmpty | p99 | 8ms | 6ms | -2ms | -25.96
| StatusStore.GetByIds | p99 | 9ms | 7ms | -2ms | -22.81
| EmojiStore.GetByName | p99 | 9ms | 7ms | -2ms | -22.32
| ChannelStore.GetMemberLastViewedAt | p99 | 15ms | 12ms | -3ms | -19.70
| SessionStore.Save | p99 | 31ms | 25ms | -6ms | -19.58
| ChannelStore.GetMembersForUser | p99 | 16ms | 13ms | -3ms | -18.49
| ChannelStore.Get | p99 | 17ms | 14ms | -3ms | -18.10
| ThreadStore.GetTotalThreads | p99 | 17ms | 14ms | -3ms | -18.01
| ThreadStore.GetTotalUnreadThreads | p99 | 17ms | 14ms | -3ms | -17.69
| PostStore.GetPostIdAfterTime | p99 | 17ms | 14ms | -3ms | -17.22
| UserTermsOfServiceStore.GetByUser | p99 | 19ms | 16ms | -3ms | -16.19
| ChannelStore.GetChannelsByUser | p99 | 19ms | 16ms | -3ms | -15.93
| GroupStore.GetGroups | p99 | 13ms | 11ms | -2ms | -14.96
| ChannelStore.IncrementMentionCount | p99 | 20ms | 17ms | -3ms | -14.96
| JobStore.GetAllByStatus | p99 | 20ms | 17ms | -3ms | -14.76
| UserStore.Get | p99 | 14ms | 12ms | -2ms | -14.33
| PostPriorityStore.GetForPosts | p99 | 15ms | 13ms | -2ms | -13.65
| ThreadStore.GetThreadsForUser | p99 | 16ms | 14ms | -2ms | -12.37
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 17ms | 15ms | -2ms | -11.94
| PluginStore.Delete | p99 | 17ms | 15ms | -2ms | -11.52
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 17ms | 15ms | -2ms | -11.51
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 18ms | 16ms | -2ms | -10.96
| TeamStore.GetTeamsByUserId | p99 | 19ms | 17ms | -2ms | -10.66
| TeamStore.GetAllPage | p99 | 19ms | 17ms | -2ms | -10.64
| SystemStore.GetByName | p99 | 19ms | 17ms | -2ms | -10.64
| TeamStore.GetMember | p99 | 19ms | 17ms | -2ms | -10.32
| ThreadStore.GetTeamsUnreadForUser | p99 | 20ms | 18ms | -2ms | -9.87
| PreferenceStore.GetAll | p99 | 22ms | 20ms | -2ms | -9.28
| ChannelStore.GetAllChannelMembersForUser | p99 | 26ms | 24ms | -2ms | -7.76
| TeamStore.SaveMember | p99 | 81ms | 75ms | -6ms | -7.42
| PostStore.Update | p99 | 27ms | 25ms | -2ms | -7.34
| ProductNoticesStore.View | p99 | 137ms | 129ms | -8ms | -5.85
| UserStore.Search | p99 | 70ms | 66ms | -4ms | -5.74
| WebhookStore.GetOutgoingByTeam | p99 | 36ms | 34ms | -2ms | -5.60
| PreferenceStore.Save | p99 | 49ms | 47ms | -2ms | -4.09
| UserStore.Save | p99 | 212ms | 205ms | -7ms | -3.31
| ChannelStore.SaveMember | p99 | 95ms | 92ms | -3ms | -3.16
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 88ms | 90ms | 2ms | 2.28
| uploadFileStream | avg | 347ms | 354ms | 7ms | 2.02
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getPublicChannelsForTeam | p99 | 25ms | 51ms | 26ms | 104.03
| getTeamMember | p99 | 7ms | 14ms | 7ms | 96.92
| patchPost | p99 | 55ms | 99ms | 44ms | 79.99
| getChannel | p99 | 9ms | 16ms | 7ms | 76.93
| getDrafts | p99 | 13ms | 16ms | 3ms | 22.53
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | avg | 36ms | 0s | -36ms | -98.73
| getChannelMembers | avg | 5ms | 3ms | -2ms | -40.73
| logout | avg | 35ms | 25ms | -10ms | -28.19
| autocompleteChannelsForTeamForSearch | avg | 36ms | 30ms | -6ms | -16.85
| updateCategoriesForTeamForUser | avg | 63ms | 53ms | -10ms | -15.82
| unfollowThreadByUser | avg | 15ms | 13ms | -2ms | -13.32
| createChannelBookmark | avg | 18ms | 16ms | -2ms | -11.06
| deletePost | avg | 23ms | 21ms | -2ms | -8.83
| createChannel | avg | 194ms | 183ms | -11ms | -5.66
| getProfileImage | avg | 71ms | 67ms | -4ms | -5.65
| addChannelMember | avg | 193ms | 185ms | -8ms | -4.15
| createDirectChannel | avg | 198ms | 192ms | -6ms | -3.03
| createPost | avg | 191ms | 186ms | -5ms | -2.62
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 50ms | 0s | -50ms | -100.50
| unfollowThreadByUser | p99 | 167ms | 25ms | -142ms | -84.78
| logout | p99 | 96ms | 50ms | -46ms | -47.67
| getChannelUnread | p99 | 9ms | 5ms | -4ms | -44.41
| autocompleteChannelsForTeamForSearch | p99 | 175ms | 98ms | -77ms | -43.99
| getPostThread | p99 | 39ms | 25ms | -14ms | -35.72
| getChannelMembersForTeamForUser | p99 | 16ms | 13ms | -3ms | -18.21
| getChannelsForUser | p99 | 19ms | 16ms | -3ms | -15.93
| getPostsForChannel | p99 | 163ms | 142ms | -21ms | -12.92
| getUser | p99 | 25ms | 22ms | -3ms | -12.21
| saveReaction | p99 | 34ms | 30ms | -4ms | -11.59
| getPostsForChannelAroundLastUnread | p99 | 74ms | 66ms | -8ms | -10.77
| getTeamsForUser | p99 | 19ms | 17ms | -2ms | -10.54
| getChannelMember | p99 | 41ms | 37ms | -4ms | -9.84
| getUsers | p99 | 24ms | 22ms | -2ms | -8.50
| getClientConfig | p99 | 41ms | 38ms | -3ms | -7.27
| searchUsers | p99 | 74ms | 70ms | -4ms | -5.43
| viewChannel | p99 | 43ms | 41ms | -2ms | -4.63
| createUser | p99 | 394ms | 376ms | -18ms | -4.57
| createPost | p99 | 857ms | 831ms | -26ms | -3.03
| addTeamMember | p99 | 2.24s | 2.198s | -42ms | -1.88
| addChannelMember | p99 | 485ms | 476ms | -9ms | -1.86
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 5ms | 1ms | 22.647
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.471
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.670
| ChannelBookmarkStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 32ms | -1ms | -3.048
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 36ms| 30ms | -6ms | -16.875
| |  P99| 175ms| 98ms | -77ms | -43.991
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 22ms | 1ms | 4.654
| |  P99| 50ms| 68ms | 18ms | 36.283
| ChannelStore.CreateInitialSidebarCategories |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 81ms| 81ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 34ms| 0s | -34ms | -98.678
| |  P99| 50ms| 0s | -50ms | -100.503
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -18.098
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 3ms | -1ms | -28.103
| |  P99| 26ms| 24ms | -2ms | -7.756
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 17ms | 2ms | 13.737
| |  P99| 156ms| 165ms | 9ms | 5.770
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 38ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.412
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.223
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.930
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.308
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.816
| ChannelStore.GetGuestCount |  Avg| 3ms| 2ms | -1ms | -39.839
| |  P99| 23ms| 22ms | -1ms | -4.292
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 6.946
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -19.697
| ChannelStore.GetMembers |  Avg| 2ms| 3ms | 1ms | 40.771
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 13ms | -3ms | -18.488
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 26.929
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 13ms | 1ms | 8.079
| |  P99| 25ms| 51ms | 26ms | 104.615
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 13ms| 12ms | -1ms | -7.779
| |  P99| 47ms| 46ms | -1ms | -2.124
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 6ms | -2ms | -24.037
| |  P99| 25ms| 10ms | -15ms | -61.078
| ChannelStore.GetTeamChannels |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -14.959
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.184
| ChannelStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 32ms| 34ms | 2ms | 6.300
| ChannelStore.SaveMember |  Avg| 27ms| 28ms | 1ms | 3.642
| |  P99| 95ms| 92ms | -3ms | -3.159
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.590
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 5ms | 1ms | 22.604
| |  P99| 15ms| 14ms | -1ms | -6.732
| ChannelStore.UpdateSidebarCategories |  Avg| 45ms| 39ms | -6ms | -13.452
| |  P99| 88ms| 50ms | -38ms | -43.386
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -18.040
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 5ms | 1ms | 25.892
| |  P99| 22ms| 31ms | 9ms | 40.769
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.760
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 22.533
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.316
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.812
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.725
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 13ms | 8ms | 160.275
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.001
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.950
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.079
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 11ms | -1ms | -8.550
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 6.013
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -14.960
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -14.758
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 44.351
| |  P99| 38ms| 38ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 28.718
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 38ms | 33ms | 666.667
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -55.710
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 5ms | 1ms | 26.755
| |  P99| 5ms| 24ms | 19ms | 383.838
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.521
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 9ms | -11ms | -56.122
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 8ms | -6ms | -42.251
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.825
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 1ms | -1ms | -65.070
| |  P99| 7ms| 5ms | -2ms | -27.905
| PostPriorityStore.GetForPost |  Avg| 2ms| 1ms | -1ms | -63.320
| |  P99| 12ms| 6ms | -6ms | -49.587
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.650
| PostStore.AnalyticsPostCount |  Avg| 506ms| 260ms | -246ms | -48.580
| |  P99| 995ms| 498ms | -497ms | -49.950
| PostStore.Delete |  Avg| 16ms| 14ms | -2ms | -12.339
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 8.990
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.219
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.186
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.603
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.224
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.447
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.191
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 81ms| 83ms | 2ms | 2.476
| |  P99| 924ms| 928ms | 4ms | 0.433
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 13.557
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.338
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.440
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.276
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 49ms| 47ms | -2ms | -4.089
| ProductNoticesStore.ClearOldNotices |  Avg| 14ms| 13ms | -1ms | -7.211
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 36ms | 1ms | 2.846
| |  P99| 137ms| 129ms | -8ms | -5.851
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -29.497
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.260
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.789
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.956
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.942
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 2ms | -1ms | -31.529
| |  P99| 22ms| 5ms | -17ms | -76.233
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 35ms| 36ms | 1ms | 2.884
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 31ms| 25ms | -6ms | -19.577
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.271
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.810
| StatusStore.SaveOrUpdate |  Avg| 4ms| 20ms | 16ms | 402.921
| |  P99| 18ms| 295ms | 277ms | 1527.591
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 12ms | -8ms | -39.024
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.637
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.641
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 16ms | -2ms | -10.960
| TeamStore.GetMember |  Avg| 3ms| 2ms | -1ms | -38.795
| |  P99| 19ms| 17ms | -2ms | -10.320
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.662
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.494
| TeamStore.GetTotalMemberCount |  Avg| 36ms| 19ms | -17ms | -47.708
| |  P99| 50ms| 25ms | -25ms | -50.251
| TeamStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 81ms| 75ms | -6ms | -7.421
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.867
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.382
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.079
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 14ms | -2ms | -12.366
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -18.012
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.161
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.686
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -11.507
| ThreadStore.MaintainMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.192
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.700
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 2ms | 1ms | 70.482
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 37ms| 36ms | -1ms | -2.737
| |  P99| 170ms| 169ms | -1ms | -0.587
| UserStore.Count |  Avg| 10ms| 9ms | -1ms | -10.487
| |  P99| 25ms| 24ms | -1ms | -4.041
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.334
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 14ms | -5ms | -26.990
| UserStore.GetAllProfilesInChannel |  Avg| 157ms| 156ms | -1ms | -0.635
| |  P99| 481ms| 478ms | -3ms | -0.624
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 5ms | -16ms | -76.297
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.192
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.777
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.243
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.959
| UserStore.Save |  Avg| 73ms| 73ms | 0s | 0.000
| |  P99| 212ms| 205ms | -7ms | -3.309
| UserStore.Search |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 70ms| 66ms | -4ms | -5.740
| UserStore.Update |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.553
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.123
| UserStore.UpdateLastLogin |  Avg| 5ms| 6ms | 1ms | 18.757
| |  P99| 22ms| 23ms | 1ms | 4.501
| UserStore.UpdateUpdateAt |  Avg| 5ms| 6ms | 1ms | 18.863
| |  P99| 22ms| 22ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -16.194
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 36ms| 34ms | -2ms | -5.604
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 193ms| 185ms | -8ms | -4.150
| | P99| 485ms| 476ms | -9ms | -1.855
| addTeamMember | Avg| 629ms| 624ms | -5ms | -0.795
| | P99| 2.24s| 2.198s | -42ms | -1.875
| autocompleteChannelsForTeamForSearch | Avg| 36ms| 30ms | -6ms | -16.845
| | P99| 175ms| 98ms | -77ms | -43.991
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 149ms| 148ms | -1ms | -0.672
| createCategoryForTeamForUser | Avg| 36ms| 0s | -36ms | -98.730
| | P99| 50ms| 0s | -50ms | -100.503
| createChannel | Avg| 194ms| 183ms | -11ms | -5.661
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 18ms| 16ms | -2ms | -11.058
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 198ms| 192ms | -6ms | -3.027
| | P99| 488ms| 490ms | 2ms | 0.410
| createGroupChannel | Avg| 279ms| 277ms | -2ms | -0.717
| | P99| 497ms| 496ms | -1ms | -0.201
| createPost | Avg| 191ms| 186ms | -5ms | -2.619
| | P99| 857ms| 831ms | -26ms | -3.032
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| createUser | Avg| 122ms| 123ms | 1ms | 0.820
| | P99| 394ms| 376ms | -18ms | -4.572
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 23ms| 21ms | -2ms | -8.832
| | P99| 48ms| 47ms | -1ms | -2.094
| followThreadByUser | Avg| 14ms| 13ms | -1ms | -7.312
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.795
| getCategoriesForTeamForUser | Avg| 13ms| 12ms | -1ms | -7.412
| | P99| 49ms| 48ms | -1ms | -2.054
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 16ms | 7ms | 76.928
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 41ms| 37ms | -4ms | -9.838
| getChannelMembers | Avg| 5ms| 3ms | -2ms | -40.731
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 13ms | -3ms | -18.210
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 27ms| 26ms | -1ms | -3.703
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 5ms | -4ms | -44.412
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 16ms | -3ms | -15.930
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 41ms| 38ms | -3ms | -7.272
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 16ms | 3ms | 22.533
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 95ms| 94ms | -1ms | -1.057
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 88ms| 87ms | -1ms | -1.131
| getPostThread | Avg| 9ms| 10ms | 1ms | 11.236
| | P99| 39ms| 25ms | -14ms | -35.716
| getPostsForChannel | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 163ms| 142ms | -21ms | -12.916
| getPostsForChannelAroundLastUnread | Avg| 16ms| 15ms | -1ms | -6.418
| | P99| 74ms| 66ms | -8ms | -10.765
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.539
| getProfileImage | Avg| 71ms| 67ms | -4ms | -5.654
| | P99| 249ms| 249ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 13ms| 14ms | 1ms | 7.461
| | P99| 25ms| 51ms | 26ms | 104.034
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 14ms | 7ms | 96.921
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.063
| getTeamStats | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 17ms | -2ms | -10.536
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.026
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.757
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 22ms | -3ms | -12.210
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 3ms | -1ms | -27.860
| | P99| 24ms| 22ms | -2ms | -8.501
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.387
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 63ms| 64ms | 1ms | 1.589
| | P99| 248ms| 247ms | -1ms | -0.404
| logout | Avg| 35ms| 25ms | -10ms | -28.194
| | P99| 96ms| 50ms | -46ms | -47.669
| patchPost | Avg| 25ms| 26ms | 1ms | 3.940
| | P99| 55ms| 99ms | 44ms | 79.989
| removeUserCustomStatus | Avg| 127ms| 126ms | -1ms | -0.786
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 34ms| 30ms | -4ms | -11.595
| searchAllChannels | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.533
| searchPostsInTeam | Avg| 88ms| 90ms | 2ms | 2.275
| | P99| 933ms| 928ms | -5ms | -0.536
| searchUsers | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 74ms| 70ms | -4ms | -5.431
| setPostReminder | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 15ms| 13ms | -2ms | -13.322
| | P99| 167ms| 25ms | -142ms | -84.778
| updateCategoriesForTeamForUser | Avg| 63ms| 53ms | -10ms | -15.824
| | P99| 99ms| 99ms | 0s | 0.000
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 96ms| 97ms | 1ms | 1.041
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 347ms| 354ms | 7ms | 2.017
| | P99| 970ms| 974ms | 4ms | 0.412
| upsertDraft | Avg| 4ms| 5ms | 1ms | 22.340
| | P99| 20ms| 19ms | -1ms | -5.021
| viewChannel | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 43ms| 41ms | -2ms | -4.632
