### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 88ms | 90ms | 2ms | 2.26
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.List | p99 | 5ms | 20ms | 15ms | 303.03
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 20ms | 15ms | 303.03
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| ChannelStore.GetFileCount | p99 | 10ms | 22ms | 12ms | 120.65
| JobStore.GetCountByStatusAndType | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.Get | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.Save | p99 | 27ms | 43ms | 16ms | 59.81
| ChannelStore.GetSidebarCategory | p99 | 22ms | 32ms | 10ms | 45.37
| TeamStore.SaveMember | p99 | 103ms | 146ms | 43ms | 41.77
| ThreadStore.GetTotalThreads | p99 | 10ms | 14ms | 4ms | 40.87
| UserStore.GetByUsername | p99 | 5ms | 7ms | 2ms | 40.19
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 10ms | 14ms | 4ms | 39.81
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 5ms | 7ms | 2ms | 37.64
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 25ms | 34ms | 9ms | 36.08
| ThreadStore.GetTotalUnreadThreads | p99 | 10ms | 13ms | 3ms | 30.89
| PreferenceStore.DeleteCategoryAndName | p99 | 18ms | 22ms | 4ms | 22.28
| ChannelStore.GetMembersForUser | p99 | 9ms | 11ms | 2ms | 21.80
| StatusStore.Get | p99 | 16ms | 19ms | 3ms | 18.75
| SessionStore.Save | p99 | 30ms | 35ms | 5ms | 16.44
| ThreadStore.GetTeamsUnreadForUser | p99 | 18ms | 21ms | 3ms | 16.36
| SessionStore.Remove | p99 | 15ms | 17ms | 2ms | 12.99
| ChannelStore.UpdateSidebarCategories | p99 | 85ms | 96ms | 11ms | 12.92
| ThreadStore.GetTotalUnreadMentions | p99 | 18ms | 20ms | 2ms | 10.98
| ChannelStore.GetTeamChannels | p99 | 50ms | 55ms | 5ms | 10.05
| JobStore.GetAllByStatus | p99 | 20ms | 22ms | 2ms | 9.84
| PostStore.Update | p99 | 43ms | 47ms | 4ms | 9.35
| ChannelStore.GetMemberCount | p99 | 173ms | 185ms | 12ms | 6.94
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.37s | 2.471s | 101ms | 4.26
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | avg | 148ms | 102ms | -46ms | -31.00
| UserStore.Count | avg | 46ms | 40ms | -6ms | -12.96
| PostStore.AnalyticsPostCount | avg | 4.266s | 3.862s | -404ms | -9.47
| ChannelStore.AutocompleteInTeamForSearch | avg | 212ms | 206ms | -6ms | -2.82
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | p99 | 3.415s | 792ms | -2.623s | -76.81
| PostStore.Delete | p99 | 90ms | 25ms | -65ms | -72.42
| JobStore.Save | p99 | 22ms | 10ms | -12ms | -53.45
| ThreadStore.MarkAllAsReadByTeam | p99 | 19ms | 10ms | -9ms | -48.26
| UserAccessTokenStore.GetByToken | p99 | 16ms | 9ms | -7ms | -44.76
| PostStore.GetPostsBefore | p99 | 30ms | 18ms | -12ms | -39.84
| ChannelStore.CreateSidebarCategory | p99 | 66ms | 50ms | -16ms | -24.06
| PostStore.GetPostsAfter | p99 | 9ms | 7ms | -2ms | -21.89
| ThreadStore.MarkAsRead | p99 | 14ms | 11ms | -3ms | -21.11
| FileInfoStore.AttachToPost | p99 | 25ms | 20ms | -5ms | -20.37
| ThreadStore.GetThreadsForUser | p99 | 12ms | 10ms | -2ms | -17.19
| ChannelStore.GetChannels | p99 | 14ms | 12ms | -2ms | -14.18
| PostStore.GetPosts | p99 | 57ms | 50ms | -7ms | -12.34
| ReactionStore.Save | p99 | 28ms | 25ms | -3ms | -10.78
| FileInfoStore.Save | p99 | 21ms | 19ms | -2ms | -9.39
| ClusterDiscoveryStore.SetLastPingAt | p99 | 22ms | 20ms | -2ms | -9.06
| UserStore.GetUnreadCount | p99 | 646ms | 603ms | -43ms | -6.66
| ChannelStore.CreateInitialSidebarCategories | p99 | 93ms | 89ms | -4ms | -4.29
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 72ms | 69ms | -3ms | -4.19
| ChannelStore.GetMembers | p99 | 224ms | 217ms | -7ms | -3.13
| UserStore.Save | p99 | 180ms | 175ms | -5ms | -2.78
| UserStore.GetAllProfiles | p99 | 225ms | 219ms | -6ms | -2.67
| ChannelStore.SaveMember | p99 | 79ms | 77ms | -2ms | -2.52
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 13ms | 15ms | 2ms | 14.90
| patchPost | avg | 99ms | 104ms | 5ms | 5.07
| removeUserCustomStatus | avg | 124ms | 128ms | 4ms | 3.23
| createPost | avg | 295ms | 299ms | 4ms | 1.36
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTopThreadsForUserSince | p99 | 36ms | 71ms | 35ms | 97.91
| setPostReminder | p99 | 25ms | 47ms | 22ms | 88.51
| getChannelMembers | p99 | 10ms | 16ms | 6ms | 60.35
| updateCategoriesForTeamForUser | p99 | 99ms | 158ms | 59ms | 59.63
| getChannel | p99 | 12ms | 16ms | 4ms | 33.26
| getChannelMember | p99 | 14ms | 18ms | 4ms | 29.19
| getCategoriesForTeamForUser | p99 | 27ms | 34ms | 7ms | 26.38
| getChannelMembersForTeamForUser | p99 | 15ms | 17ms | 2ms | 13.20
| updateUserCustomStatus | p99 | 358ms | 405ms | 47ms | 13.14
| createChannel | p99 | 50ms | 55ms | 5ms | 10.04
| removeUserCustomStatus | p99 | 249ms | 270ms | 21ms | 8.44
| getChannelStats | p99 | 192ms | 202ms | 10ms | 5.20
| autocompleteChannelsForTeamForSearch | p99 | 2.37s | 2.471s | 101ms | 4.26
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 154ms | 108ms | -46ms | -29.88
| getProfileImage | avg | 125ms | 103ms | -22ms | -17.56
| deletePost | avg | 20ms | 18ms | -2ms | -9.94
| uploadFileStream | avg | 444ms | 426ms | -18ms | -4.06
| autocompleteUsers | avg | 82ms | 79ms | -3ms | -3.67
| autocompleteChannelsForTeamForSearch | avg | 212ms | 206ms | -6ms | -2.82
| createGroupChannel | avg | 338ms | 331ms | -7ms | -2.07
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 463ms | 81ms | -382ms | -82.59
| searchPostsInTeam | p99 | 3.415s | 888ms | -2.527s | -74.00
| deletePost | p99 | 144ms | 45ms | -99ms | -68.63
| updateReadStateAllThreadsByUser | p99 | 19ms | 10ms | -9ms | -48.26
| getFilePreview | p99 | 140ms | 101ms | -39ms | -27.79
| followThreadByUser | p99 | 46ms | 37ms | -9ms | -19.40
| uploadFileStream | p99 | 1.132s | 994ms | -138ms | -12.19
| createCategoryForTeamForUser | p99 | 76ms | 68ms | -8ms | -10.52
| getProfileImage | p99 | 461ms | 429ms | -32ms | -6.94
| getFileThumbnail | p99 | 94ms | 91ms | -3ms | -3.20
| getUsers | p99 | 228ms | 223ms | -5ms | -2.20
| createGroupChannel | p99 | 906ms | 890ms | -16ms | -1.77
| getPostsForChannel | p99 | 407ms | 401ms | -6ms | -1.47
| autocompleteUsers | p99 | 397ms | 392ms | -5ms | -1.26
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 49ms| 48ms | -1ms | -2.027
| |  P99| 238ms| 236ms | -2ms | -0.842
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 212ms| 206ms | -6ms | -2.825
| |  P99| 2.37s| 2.471s | 101ms | 4.262
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.087
| ChannelStore.CreateInitialSidebarCategories |  Avg| 22ms| 21ms | -1ms | -4.643
| |  P99| 93ms| 89ms | -4ms | -4.295
| ChannelStore.CreateSidebarCategory |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 66ms| 50ms | -16ms | -24.060
| ChannelStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 72ms| 69ms | -3ms | -4.194
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.194
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.177
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.650
| ChannelStore.GetGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 9ms| 10ms | 1ms | 10.725
| |  P99| 173ms| 185ms | 12ms | 6.936
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 12ms| 11ms | -1ms | -8.508
| |  P99| 224ms| 217ms | -7ms | -3.127
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 21.795
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 6ms | 1ms | 18.336
| |  P99| 25ms| 34ms | 9ms | 36.084
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 32ms | 10ms | 45.366
| ChannelStore.GetTeamChannels |  Avg| 26ms| 25ms | -1ms | -3.912
| |  P99| 50ms| 55ms | 5ms | 10.050
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannel |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateMemberCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidatePinnedPostCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 27ms| 43ms | 16ms | 59.813
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 79ms| 77ms | -2ms | -2.517
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.108
| ChannelStore.UpdateLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 85ms| 96ms | 11ms | 12.922
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.094
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.060
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 20ms | -5ms | -20.367
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 6ms| 5ms | -1ms | -17.581
| |  P99| 21ms| 19ms | -2ms | -9.392
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.466
| GroupStore.GetByName |  Avg| 1ms| 2ms | 1ms | 67.643
| |  P99| 19ms| 20ms | 1ms | 5.282
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.838
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 105.663
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 3ms | 1ms | 57.783
| |  P99| 5ms| 20ms | 15ms | 303.030
| JobStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 10ms | -12ms | -53.452
| JobStore.UpdateOptimistically |  Avg| 5ms| 4ms | -1ms | -20.682
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 5ms | 1ms | 22.637
| |  P99| 9ms| 10ms | 1ms | 10.811
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 2ms | 1ms | 86.494
| |  P99| 5ms| 20ms | 15ms | 303.030
| PluginStore.SetWithOptions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.060
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 4.266s| 3.862s | -404ms | -9.471
| |  P99| 4.977s| 4.975s | -2ms | -0.040
| PostStore.Delete |  Avg| 15ms| 14ms | -1ms | -6.588
| |  P99| 90ms| 25ms | -65ms | -72.424
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.641
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.740
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 5ms | -1ms | -17.780
| |  P99| 57ms| 50ms | -7ms | -12.341
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -21.893
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 18ms | -12ms | -39.835
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 9ms| 8ms | -1ms | -10.744
| |  P99| 49ms| 48ms | -1ms | -2.059
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 148ms| 102ms | -46ms | -30.999
| |  P99| 3.415s| 792ms | -2.623s | -76.808
| PostStore.SetPostReminder |  Avg| 8ms| 9ms | 1ms | 12.099
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 43ms| 47ms | 4ms | 9.350
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.284
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.836
| PreferenceStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 37ms| 38ms | 1ms | 2.675
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.778
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.421
| SessionStore.GetSessionsExpired |  Avg| 2ms| 1ms | -1ms | -61.949
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 37.641
| SessionStore.Remove |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 12.987
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 30ms| 35ms | 5ms | 16.440
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.598
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 18.755
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.205
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.515
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.297
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 66ms| 67ms | 1ms | 1.510
| |  P99| 103ms| 146ms | 43ms | 41.771
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 21ms | 3ms | 16.360
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.723
| ThreadStore.GetThreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.881
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -17.195
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.867
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.983
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.887
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 39.806
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -39.184
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 3ms | -1ms | -25.062
| |  P99| 19ms| 10ms | -9ms | -48.257
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.112
| ThreadStore.UpdateMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.939
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 9ms | -7ms | -44.758
| UserStore.AutocompleteUsersInChannel |  Avg| 127ms| 127ms | 0s | 0.000
| |  P99| 444ms| 446ms | 2ms | 0.451
| UserStore.Count |  Avg| 46ms| 40ms | -6ms | -12.964
| |  P99| 95ms| 95ms | 0s | 0.000
| UserStore.Get |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 10ms| 9ms | -1ms | -9.752
| |  P99| 225ms| 219ms | -6ms | -2.670
| UserStore.GetAllProfilesInChannel |  Avg| 191ms| 190ms | -1ms | -0.523
| |  P99| 943ms| 939ms | -4ms | -0.424
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.191
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.144
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 646ms| 603ms | -43ms | -6.658
| UserStore.GetUnreadCountForChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 88ms| 90ms | 2ms | 2.263
| |  P99| 247ms| 248ms | 1ms | 0.404
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.102
| UserStore.Save |  Avg| 70ms| 69ms | -1ms | -1.437
| |  P99| 180ms| 175ms | -5ms | -2.779
| UserStore.Search |  Avg| 42ms| 41ms | -1ms | -2.405
| |  P99| 245ms| 245ms | 0s | 0.000
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.130
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 181ms| 181ms | 0s | 0.000
| | P99| 471ms| 472ms | 1ms | 0.212
| addTeamMember | Avg| 939ms| 936ms | -3ms | -0.319
| | P99| 2.456s| 2.452s | -4ms | -0.163
| autocompleteChannelsForTeamForSearch | Avg| 212ms| 206ms | -6ms | -2.824
| | P99| 2.37s| 2.471s | 101ms | 4.262
| autocompleteUsers | Avg| 82ms| 79ms | -3ms | -3.669
| | P99| 397ms| 392ms | -5ms | -1.261
| createCategoryForTeamForUser | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 76ms| 68ms | -8ms | -10.516
| createChannel | Avg| 26ms| 25ms | -1ms | -3.891
| | P99| 50ms| 55ms | 5ms | 10.045
| createDirectChannel | Avg| 215ms| 217ms | 2ms | 0.932
| | P99| 493ms| 494ms | 1ms | 0.203
| createGroupChannel | Avg| 338ms| 331ms | -7ms | -2.074
| | P99| 906ms| 890ms | -16ms | -1.767
| createPost | Avg| 295ms| 299ms | 4ms | 1.356
| | P99| 989ms| 993ms | 4ms | 0.404
| createUser | Avg| 98ms| 98ms | 0s | 0.000
| | P99| 244ms| 245ms | 1ms | 0.409
| deletePost | Avg| 20ms| 18ms | -2ms | -9.939
| | P99| 144ms| 45ms | -99ms | -68.631
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 46ms| 37ms | -9ms | -19.397
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 27ms| 34ms | 7ms | 26.379
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 16ms | 4ms | 33.264
| getChannelMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 18ms | 4ms | 29.192
| getChannelMembers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 60.352
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 17ms | 2ms | 13.198
| getChannelStats | Avg| 11ms| 12ms | 1ms | 9.227
| | P99| 192ms| 202ms | 10ms | 5.199
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 6ms | -1ms | -14.731
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 20ms | -1ms | -4.866
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 42ms| 43ms | 1ms | 2.377
| getFilePreview | Avg| 35ms| 34ms | -1ms | -2.873
| | P99| 140ms| 101ms | -39ms | -27.785
| getFileThumbnail | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 94ms| 91ms | -3ms | -3.200
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 35ms| 34ms | -1ms | -2.861
| | P99| 407ms| 401ms | -6ms | -1.474
| getPostsForChannelAroundLastUnread | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 111ms| 111ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.735
| getProfileImage | Avg| 125ms| 103ms | -22ms | -17.561
| | P99| 461ms| 429ms | -32ms | -6.938
| getPublicChannelsForTeam | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.458
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 17ms | 1ms | 6.208
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 12ms | -1ms | -7.681
| getTopThreadsForTeamSince | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTopThreadsForUserSince | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 36ms| 71ms | 35ms | 97.906
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.539
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 13ms| 12ms | -1ms | -7.980
| | P99| 228ms| 223ms | -5ms | -2.196
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 99ms| 100ms | 1ms | 1.015
| | P99| 459ms| 461ms | 2ms | 0.436
| logout | Avg| 38ms| 39ms | 1ms | 2.608
| | P99| 94ms| 95ms | 1ms | 1.060
| patchPost | Avg| 99ms| 104ms | 5ms | 5.068
| | P99| 463ms| 81ms | -382ms | -82.592
| removeUserCustomStatus | Avg| 124ms| 128ms | 4ms | 3.226
| | P99| 249ms| 270ms | 21ms | 8.443
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 16ms| 15ms | -1ms | -6.360
| | P99| 47ms| 47ms | 0s | 0.000
| searchAllChannels | Avg| 50ms| 49ms | -1ms | -2.015
| | P99| 238ms| 237ms | -1ms | -0.421
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| searchPostsInTeam | Avg| 154ms| 108ms | -46ms | -29.882
| | P99| 3.415s| 888ms | -2.527s | -73.997
| searchUsers | Avg| 45ms| 44ms | -1ms | -2.226
| | P99| 245ms| 245ms | 0s | 0.000
| setPostReminder | Avg| 13ms| 15ms | 2ms | 14.897
| | P99| 25ms| 47ms | 22ms | 88.512
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 9.889
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 44ms| 44ms | 0s | 0.000
| | P99| 99ms| 158ms | 59ms | 59.629
| updatePreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 10ms | -9ms | -48.257
| updateReadStateThreadByUser | Avg| 22ms| 21ms | -1ms | -4.569
| | P99| 50ms| 49ms | -1ms | -2.010
| updateUserCustomStatus | Avg| 136ms| 136ms | 0s | 0.000
| | P99| 358ms| 405ms | 47ms | 13.135
| uploadFileStream | Avg| 444ms| 426ms | -18ms | -4.057
| | P99| 1.132s| 994ms | -138ms | -12.185
| viewChannel | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 45ms| 45ms | 0s | 0.000
