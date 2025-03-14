### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetTeamChannels | avg | 8ms | 15ms | 7ms | 82.96
| PostStore.SearchPostsForUser | avg | 28ms | 45ms | 17ms | 60.42
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 8ms | 10ms | 2ms | 25.07
| UserStore.GetProfilesInChannel | avg | 26ms | 31ms | 5ms | 19.59
| TeamStore.GetActiveMemberCount | avg | 36ms | 38ms | 2ms | 5.54
| UserStore.GetAllProfilesInChannel | avg | 153ms | 159ms | 6ms | 3.92
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetTeamChannels | p99 | 10ms | 90ms | 80ms | 803.85
| RoleStore.GetByNames | p99 | 5ms | 32ms | 27ms | 545.45
| PostStore.SetPostReminder | p99 | 10ms | 42ms | 32ms | 321.61
| SessionStore.Remove | p99 | 10ms | 38ms | 28ms | 288.29
| UserAccessTokenStore.GetByToken | p99 | 5ms | 19ms | 14ms | 282.83
| PostStore.GetPostReminderMetadata | p99 | 5ms | 16ms | 11ms | 222.19
| DraftStore.GetDraftsForUser | p99 | 7ms | 18ms | 11ms | 164.70
| ChannelStore.GetAllChannelMembersForUser | p99 | 11ms | 29ms | 18ms | 163.41
| UserStore.Update | p99 | 26ms | 68ms | 42ms | 159.99
| PostStore.SearchPostsForUser | p99 | 591ms | 1.484s | 893ms | 150.99
| JobStore.UpdateOptimistically | p99 | 9ms | 22ms | 13ms | 147.45
| UserStore.GetByUsername | p99 | 5ms | 12ms | 7ms | 140.01
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| TeamStore.GetTotalMemberCount | p99 | 50ms | 90ms | 40ms | 80.50
| TeamStore.GetActiveMemberCount | p99 | 50ms | 90ms | 40ms | 80.40
| RoleStore.ChannelHigherScopedPermissions | p99 | 8ms | 14ms | 6ms | 78.43
| PostPersistentNotificationStore.DeleteExpired | p99 | 8ms | 14ms | 6ms | 76.43
| LinkMetadataStore.Save | p99 | 10ms | 17ms | 7ms | 71.63
| JobStore.Save | p99 | 14ms | 23ms | 9ms | 62.72
| StatusStore.UpdateExpiredDNDStatuses | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 145ms | 53ms | 57.77
| ChannelStore.IsReadOnlyChannel | p99 | 5ms | 8ms | 3ms | 55.44
| StatusStore.UpdateLastActivityAt | p99 | 11ms | 17ms | 6ms | 53.04
| FileInfoStore.Get | p99 | 6ms | 9ms | 3ms | 49.30
| StatusStore.Get | p99 | 6ms | 9ms | 3ms | 48.53
| JobStore.GetAllByStatus | p99 | 15ms | 22ms | 7ms | 47.23
| ThreadStore.GetThreadsForUser | p99 | 12ms | 17ms | 5ms | 43.45
| ChannelStore.GetChannelsByUser | p99 | 5ms | 7ms | 2ms | 40.18
| LinkMetadataStore.Get | p99 | 5ms | 7ms | 2ms | 40.03
| FileInfoStore.GetForPost | p99 | 5ms | 7ms | 2ms | 40.01
| PostStore.GetEtag | p99 | 11ms | 15ms | 4ms | 37.09
| StatusStore.GetByIds | p99 | 14ms | 19ms | 5ms | 36.36
| DraftStore.Get | p99 | 8ms | 11ms | 3ms | 35.74
| ProductNoticesStore.View | p99 | 138ms | 186ms | 48ms | 34.84
| ChannelStore.GetMemberForPost | p99 | 14ms | 19ms | 5ms | 34.82
| TeamStore.GetAllPage | p99 | 6ms | 8ms | 2ms | 32.22
| UserStore.GetProfileByIds | p99 | 10ms | 13ms | 3ms | 30.59
| DraftStore.Delete | p99 | 10ms | 13ms | 3ms | 30.51
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 7ms | 9ms | 2ms | 29.65
| UserStore.Search | p99 | 53ms | 68ms | 15ms | 28.33
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 7ms | 9ms | 2ms | 27.90
| TeamStore.GetTeamsForUser | p99 | 7ms | 9ms | 2ms | 27.44
| ChannelStore.Get | p99 | 8ms | 10ms | 2ms | 25.79
| ChannelStore.GetFileCount | p99 | 8ms | 10ms | 2ms | 24.77
| ClusterDiscoveryStore.SetLastPingAt | p99 | 20ms | 24ms | 4ms | 19.98
| ChannelStore.SearchGroupChannels | p99 | 19ms | 22ms | 3ms | 15.94
| PostStore.GetPostsBefore | p99 | 13ms | 15ms | 2ms | 15.13
| ChannelStore.SaveMember | p99 | 74ms | 85ms | 11ms | 14.87
| FileInfoStore.Save | p99 | 21ms | 24ms | 3ms | 14.37
| WebhookStore.GetOutgoingByTeam | p99 | 35ms | 40ms | 5ms | 14.36
| ThreadStore.GetThreadForUser | p99 | 24ms | 27ms | 3ms | 12.26
| PostStore.Get | p99 | 18ms | 20ms | 2ms | 10.93
| SessionStore.Get | p99 | 23ms | 25ms | 2ms | 8.85
| UserStore.Count | p99 | 23ms | 25ms | 2ms | 8.83
| ChannelStore.CreateDirectChannel | p99 | 43ms | 46ms | 3ms | 6.91
| ChannelStore.GetMemberCount | p99 | 44ms | 47ms | 3ms | 6.89
| PostStore.GetPostsSince | p99 | 45ms | 47ms | 2ms | 4.40
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 90ms | 92ms | 2ms | 2.22
| UserStore.GetAllProfilesInChannel | p99 | 472ms | 478ms | 6ms | 1.27
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | avg | 3ms | 0s | -3ms | -101.88
| StatusStore.SaveOrUpdate | avg | 19ms | 3ms | -16ms | -84.10
| ChannelStore.AutocompleteInTeamForSearch | avg | 103ms | 44ms | -59ms | -57.24
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 13ms | 9ms | -4ms | -30.34
| PostStore.Delete | avg | 18ms | 13ms | -5ms | -28.28
| PostStore.Update | avg | 15ms | 12ms | -3ms | -19.90
| PostStore.Save | avg | 13ms | 11ms | -2ms | -15.93
| ChannelStore.CreateSidebarCategory | avg | 24ms | 22ms | -2ms | -8.33
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| StatusStore.SaveOrUpdate | p99 | 394ms | 15ms | -379ms | -96.25
| ChannelStore.AutocompleteInTeamForSearch | p99 | 1.42s | 99ms | -1.321s | -93.04
| PostStore.Delete | p99 | 90ms | 25ms | -65ms | -72.22
| JobStore.GetNewestJobByStatusesAndType | p99 | 18ms | 5ms | -13ms | -71.82
| PluginStore.List | p99 | 17ms | 6ms | -11ms | -63.95
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 5ms | -5ms | -51.28
| JobStore.UpdateStatus | p99 | 14ms | 7ms | -7ms | -48.78
| ReactionStore.GetForPost | p99 | 16ms | 9ms | -7ms | -42.57
| PostStore.Update | p99 | 42ms | 25ms | -17ms | -40.54
| JobStore.GetCountByStatusAndType | p99 | 8ms | 5ms | -3ms | -36.70
| ChannelStore.GetPublicChannelsForTeam | p99 | 39ms | 25ms | -14ms | -36.00
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 17ms | 12ms | -5ms | -29.92
| PostPriorityStore.GetForPost | p99 | 7ms | 5ms | -2ms | -29.85
| UserStore.UpdateLastLogin | p99 | 19ms | 14ms | -5ms | -25.82
| JobStore.UpdateStatusOptimistically | p99 | 21ms | 16ms | -5ms | -23.31
| PostStore.GetPosts | p99 | 13ms | 10ms | -3ms | -22.80
| PreferenceStore.GetAll | p99 | 17ms | 14ms | -3ms | -17.92
| UserStore.AutocompleteUsersInChannel | p99 | 157ms | 129ms | -28ms | -17.80
| PostStore.GetPostsByThread | p99 | 18ms | 15ms | -3ms | -16.91
| SessionStore.UpdateLastActivityAt | p99 | 12ms | 10ms | -2ms | -16.16
| UserStore.UpdateUpdateAt | p99 | 20ms | 17ms | -3ms | -14.72
| AuditStore.Save | p99 | 21ms | 19ms | -2ms | -9.60
| SessionStore.Save | p99 | 21ms | 19ms | -2ms | -9.54
| PluginStore.SetWithOptions | p99 | 22ms | 20ms | -2ms | -9.29
| FileInfoStore.AttachToPost | p99 | 24ms | 22ms | -2ms | -8.46
| ChannelStore.GetByName | p99 | 26ms | 24ms | -2ms | -7.64
| UserStore.Save | p99 | 176ms | 164ms | -12ms | -6.81
| PreferenceStore.DeleteCategoryAndName | p99 | 90ms | 84ms | -6ms | -6.67
| ChannelStore.Save | p99 | 47ms | 44ms | -3ms | -6.32
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 33ms | 48ms | 15ms | 45.11
| removeUserCustomStatus | avg | 120ms | 148ms | 28ms | 23.25
| createGroupChannel | avg | 285ms | 344ms | 59ms | 20.73
| createDirectChannel | avg | 188ms | 218ms | 30ms | 15.96
| logout | avg | 28ms | 32ms | 4ms | 14.08
| createUser | avg | 136ms | 154ms | 18ms | 13.28
| createChannel | avg | 197ms | 212ms | 15ms | 7.60
| uploadFileStream | avg | 369ms | 396ms | 27ms | 7.32
| getTeamStats | avg | 36ms | 38ms | 2ms | 5.52
| updateCategoriesForTeamForUser | avg | 52ms | 54ms | 2ms | 3.84
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 50ms | 179ms | 129ms | 259.76
| setPostReminder | p99 | 25ms | 84ms | 59ms | 237.42
| getDrafts | p99 | 7ms | 18ms | 11ms | 160.70
| searchPostsInTeam | p99 | 607ms | 1.484s | 877ms | 144.56
| updateCategoriesForTeamForUser | p99 | 99ms | 197ms | 98ms | 98.78
| createChannel | p99 | 249ms | 492ms | 243ms | 97.79
| unfollowThreadByUser | p99 | 25ms | 48ms | 23ms | 92.81
| createGroupChannel | p99 | 496ms | 931ms | 435ms | 87.65
| getTeamStats | p99 | 50ms | 90ms | 40ms | 80.40
| getChannel | p99 | 8ms | 14ms | 6ms | 77.52
| getPostThread | p99 | 23ms | 35ms | 12ms | 51.76
| addTeamMember | p99 | 998ms | 1.48s | 482ms | 48.32
| getTeamMembersForUser | p99 | 10ms | 14ms | 4ms | 40.25
| getChannelsForUser | p99 | 5ms | 7ms | 2ms | 40.18
| updatePreferences | p99 | 24ms | 32ms | 8ms | 32.84
| deleteDraft | p99 | 9ms | 12ms | 3ms | 31.72
| getThreadsForUser | p99 | 13ms | 17ms | 4ms | 31.61
| searchUsers | p99 | 58ms | 71ms | 13ms | 22.24
| removeUserCustomStatus | p99 | 381ms | 465ms | 84ms | 22.03
| getUser | p99 | 14ms | 17ms | 3ms | 21.46
| viewChannel | p99 | 30ms | 36ms | 6ms | 20.20
| getChannelsForTeamForUser | p99 | 10ms | 12ms | 2ms | 20.18
| getChannelMembersForTeamForUser | p99 | 11ms | 13ms | 2ms | 18.27
| searchGroupChannels | p99 | 19ms | 22ms | 3ms | 15.74
| getTeamsUnreadForUser | p99 | 13ms | 15ms | 2ms | 14.91
| saveReaction | p99 | 24ms | 26ms | 2ms | 8.46
| createUser | p99 | 449ms | 478ms | 29ms | 6.45
| updateReadStateThreadByUser | p99 | 82ms | 87ms | 5ms | 6.13
| deletePost | p99 | 90ms | 95ms | 5ms | 5.56
| createPost | p99 | 813ms | 857ms | 44ms | 5.41
| getPostsForChannel | p99 | 92ms | 96ms | 4ms | 4.33
| getFilePreview | p99 | 95ms | 98ms | 3ms | 3.14
| getFileThumbnail | p99 | 90ms | 92ms | 2ms | 2.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 8ms | 0s | -8ms | -100.46
| updateChannelBookmark | avg | 43ms | 9ms | -34ms | -79.58
| autocompleteChannelsForTeamForSearch | avg | 103ms | 44ms | -59ms | -57.20
| patchPost | avg | 21ms | 18ms | -3ms | -13.96
| getProfileImage | avg | 74ms | 65ms | -9ms | -12.14
| createChannelBookmark | avg | 18ms | 16ms | -2ms | -11.16
| updateReadStateThreadByUser | avg | 28ms | 25ms | -3ms | -10.65
| createCategoryForTeamForUser | avg | 25ms | 23ms | -2ms | -7.99
| addTeamMember | avg | 558ms | 547ms | -11ms | -1.97
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| autocompleteChannelsForTeamForSearch | p99 | 1.42s | 99ms | -1.321s | -93.04
| updateChannelBookmark | p99 | 99ms | 25ms | -74ms | -74.75
| updateReadStateAllThreadsByUser | p99 | 10ms | 5ms | -5ms | -51.28
| createCategoryForTeamForUser | p99 | 50ms | 25ms | -25ms | -50.25
| getTeamMember | p99 | 18ms | 11ms | -7ms | -37.95
| patchPost | p99 | 68ms | 47ms | -21ms | -30.77
| getPublicChannelsForTeam | p99 | 43ms | 31ms | -12ms | -27.61
| autocompleteUsers | p99 | 129ms | 100ms | -29ms | -22.52
| getPreferences | p99 | 17ms | 14ms | -3ms | -17.34
| getChannelMember | p99 | 29ms | 26ms | -3ms | -10.36
| getProfileImage | p99 | 321ms | 309ms | -12ms | -3.74
| login | p99 | 243ms | 240ms | -3ms | -1.23
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.600
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -63.540
| |  P99| 9ms| 8ms | -1ms | -11.494
| ChannelBookmarkStore.Delete |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.007
| ChannelBookmarkStore.Save |  Avg| 9ms| 8ms | -1ms | -10.613
| |  P99| 25ms| 24ms | -1ms | -4.056
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 3ms | -1ms | -25.468
| |  P99| 17ms| 12ms | -5ms | -29.922
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 103ms| 44ms | -59ms | -57.242
| |  P99| 1.42s| 99ms | -1.321s | -93.036
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 16ms | -1ms | -5.925
| |  P99| 43ms| 46ms | 3ms | 6.915
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 18ms | -1ms | -5.277
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 24ms| 22ms | -2ms | -8.329
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.794
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 3ms | 1ms | 52.809
| |  P99| 11ms| 29ms | 18ms | 163.410
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 9ms | -4ms | -30.339
| |  P99| 88ms| 89ms | 1ms | 1.135
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 24ms | -2ms | -7.638
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.648
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -173.180
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.176
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.650
| ChannelStore.GetFileCount |  Avg| 1ms| 2ms | 1ms | 98.011
| |  P99| 8ms| 10ms | 2ms | 24.774
| ChannelStore.GetGuestCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.880
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.887
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 19ms | 5ms | 34.821
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.476
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -36.003
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 8ms| 15ms | 7ms | 82.962
| |  P99| 10ms| 90ms | 80ms | 803.852
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.902
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 55.440
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 47ms| 44ms | -3ms | -6.316
| ChannelStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 74ms| 85ms | 11ms | 14.871
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.938
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.286
| ChannelStore.UpdateSidebarCategories |  Avg| 37ms| 38ms | 1ms | 2.673
| |  P99| 92ms| 145ms | 53ms | 57.766
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.127
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 24ms | 4ms | 19.980
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 3ms | -1ms | -27.323
| |  P99| 10ms| 13ms | 3ms | 30.512
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 10ms | 2ms | 25.075
| |  P99| 90ms| 92ms | 2ms | 2.222
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 11ms | 3ms | 35.745
| DraftStore.GetDraftsForUser |  Avg| 1ms| 2ms | 1ms | 73.402
| |  P99| 7ms| 18ms | 11ms | 164.695
| DraftStore.Upsert |  Avg| 4ms| 3ms | -1ms | -24.946
| |  P99| 17ms| 18ms | 1ms | 5.859
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 0s| 1ms | 1ms | 219.927
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -14.359
| |  P99| 24ms| 22ms | -2ms | -8.461
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 49.297
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.012
| FileInfoStore.Save |  Avg| 5ms| 4ms | -1ms | -19.442
| |  P99| 21ms| 24ms | 3ms | 14.372
| FileInfoStore.SetContent |  Avg| 8ms| 7ms | -1ms | -12.946
| |  P99| 24ms| 24ms | 0s | 0.000
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.387
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 22ms | 7ms | 47.229
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.697
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -71.823
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 23ms | 9ms | 62.718
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 22ms | 13ms | 147.448
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -24.457
| |  P99| 14ms| 7ms | -7ms | -48.780
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -21.660
| |  P99| 21ms| 16ms | -5ms | -23.310
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.029
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 71.632
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -10.552
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -133.888
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 6ms | -11ms | -63.953
| PluginStore.SetWithOptions |  Avg| 6ms| 5ms | -1ms | -17.437
| |  P99| 22ms| 20ms | -2ms | -9.290
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.008
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 14ms | 6ms | 76.433
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 0s | -3ms | -101.877
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.852
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.266
| PostStore.AnalyticsPostCount |  Avg| 262ms| 261ms | -1ms | -0.381
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 18ms| 13ms | -5ms | -28.281
| |  P99| 90ms| 25ms | -65ms | -72.222
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.934
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 15ms | 4ms | 37.092
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.538
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.783
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 2ms | 1ms | 75.876
| |  P99| 5ms| 16ms | 11ms | 222.194
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.804
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.130
| PostStore.GetPostsByIds |  Avg| 1ms| 0s | -1ms | -148.106
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 4ms| 3ms | -1ms | -27.030
| |  P99| 18ms| 15ms | -3ms | -16.906
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.396
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 11ms | -2ms | -15.932
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 28ms| 45ms | 17ms | 60.419
| |  P99| 591ms| 1.484s | 893ms | 150.989
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 14.344
| |  P99| 10ms| 42ms | 32ms | 321.608
| PostStore.Update |  Avg| 15ms| 12ms | -3ms | -19.904
| |  P99| 42ms| 25ms | -17ms | -40.536
| PreferenceStore.DeleteCategoryAndName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 90ms| 84ms | -6ms | -6.667
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.633
| PreferenceStore.GetAll |  Avg| 2ms| 1ms | -1ms | -58.868
| |  P99| 17ms| 14ms | -3ms | -17.918
| PreferenceStore.Save |  Avg| 10ms| 9ms | -1ms | -10.250
| |  P99| 38ms| 39ms | 1ms | 2.640
| ProductNoticesStore.ClearOldNotices |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 33ms| 34ms | 1ms | 3.042
| |  P99| 138ms| 186ms | 48ms | 34.842
| ReactionStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.516
| |  P99| 16ms| 9ms | -7ms | -42.574
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 14ms | 6ms | 78.431
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 32ms | 27ms | 545.455
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 4ms | 1ms | 29.606
| |  P99| 23ms| 25ms | 2ms | 8.854
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 3ms | -1ms | -27.011
| |  P99| 10ms| 38ms | 28ms | 288.288
| SessionStore.Save |  Avg| 6ms| 5ms | -1ms | -18.123
| |  P99| 21ms| 19ms | -2ms | -9.543
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.163
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 48.528
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 19ms | 5ms | 36.357
| StatusStore.SaveOrUpdate |  Avg| 19ms| 3ms | -16ms | -84.104
| |  P99| 394ms| 15ms | -379ms | -96.246
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -28.229
| |  P99| 11ms| 17ms | 6ms | 53.039
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 38ms | 2ms | 5.542
| |  P99| 50ms| 90ms | 40ms | 80.402
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.217
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.901
| TeamStore.GetMany |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.855
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 27.437
| TeamStore.GetTotalMemberCount |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 50ms| 90ms | 40ms | 80.503
| TeamStore.SaveMember |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.848
| ThreadStore.GetTeamsUnreadForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.865
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.265
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 3ms | 1ms | 41.508
| |  P99| 12ms| 17ms | 5ms | 43.446
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.114
| ThreadStore.GetTotalUnreadMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.858
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.282
| ThreadStore.MarkAsRead |  Avg| 4ms| 3ms | -1ms | -24.093
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 3ms | -1ms | -27.467
| |  P99| 10ms| 9ms | -1ms | -10.109
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| UserStore.AutocompleteUsersInChannel |  Avg| 37ms| 37ms | 0s | 0.000
| |  P99| 157ms| 129ms | -28ms | -17.798
| UserStore.Count |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.825
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 153ms| 159ms | 6ms | 3.919
| |  P99| 472ms| 478ms | 6ms | 1.271
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 12ms | 7ms | 140.011
| UserStore.GetForLogin |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.491
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.586
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.153
| UserStore.GetProfilesInChannel |  Avg| 26ms| 31ms | 5ms | 19.592
| |  P99| 241ms| 243ms | 2ms | 0.830
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 3ms | -1ms | -28.329
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.239
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 70ms| 69ms | -1ms | -1.422
| |  P99| 176ms| 164ms | -12ms | -6.810
| UserStore.Search |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 53ms| 68ms | 15ms | 28.328
| UserStore.Update |  Avg| 8ms| 7ms | -1ms | -13.087
| |  P99| 26ms| 68ms | 42ms | 159.994
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 14ms | -5ms | -25.819
| UserStore.UpdateUpdateAt |  Avg| 6ms| 5ms | -1ms | -18.127
| |  P99| 20ms| 17ms | -3ms | -14.720
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 40ms | 5ms | 14.362
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 181ms| 181ms | 0s | 0.000
| | P99| 484ms| 483ms | -1ms | -0.207
| addTeamMember | Avg| 558ms| 547ms | -11ms | -1.973
| | P99| 998ms| 1.48s | 482ms | 48.319
| autocompleteChannelsForTeamForSearch | Avg| 103ms| 44ms | -59ms | -57.204
| | P99| 1.42s| 99ms | -1.321s | -93.036
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 129ms| 100ms | -29ms | -22.519
| createCategoryForTeamForUser | Avg| 25ms| 23ms | -2ms | -7.986
| | P99| 50ms| 25ms | -25ms | -50.251
| createChannel | Avg| 197ms| 212ms | 15ms | 7.595
| | P99| 249ms| 492ms | 243ms | 97.787
| createChannelBookmark | Avg| 18ms| 16ms | -2ms | -11.155
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 188ms| 218ms | 30ms | 15.963
| | P99| 489ms| 493ms | 4ms | 0.818
| createEmoji | Avg| 8ms| 0s | -8ms | -100.457
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 285ms| 344ms | 59ms | 20.730
| | P99| 496ms| 931ms | 435ms | 87.652
| createPost | Avg| 199ms| 198ms | -1ms | -0.503
| | P99| 813ms| 857ms | 44ms | 5.409
| createUser | Avg| 136ms| 154ms | 18ms | 13.281
| | P99| 449ms| 478ms | 29ms | 6.453
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 12ms | 3ms | 31.719
| deletePost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 90ms| 95ms | 5ms | 5.556
| followThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.558
| getCategoriesForTeamForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannel | Avg| 2ms| 3ms | 1ms | 45.444
| | P99| 8ms| 14ms | 6ms | 77.520
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 29ms| 26ms | -3ms | -10.363
| getChannelMembers | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 13ms | 2ms | 18.275
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.064
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 12ms | 2ms | 20.175
| getChannelsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.176
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getDrafts | Avg| 1ms| 2ms | 1ms | 67.626
| | P99| 7ms| 18ms | 11ms | 160.700
| getFilePreview | Avg| 37ms| 38ms | 1ms | 2.687
| | P99| 95ms| 98ms | 3ms | 3.144
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 90ms| 92ms | 2ms | 2.232
| getPostThread | Avg| 4ms| 5ms | 1ms | 22.992
| | P99| 23ms| 35ms | 12ms | 51.757
| getPostsForChannel | Avg| 13ms| 14ms | 1ms | 7.653
| | P99| 92ms| 96ms | 4ms | 4.334
| getPostsForChannelAroundLastUnread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 43ms| 43ms | 0s | 0.000
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 14ms | -3ms | -17.342
| getProfileImage | Avg| 74ms| 65ms | -9ms | -12.144
| | P99| 321ms| 309ms | -12ms | -3.739
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 43ms| 31ms | -12ms | -27.606
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 18ms| 11ms | -7ms | -37.949
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 14ms | 4ms | 40.253
| getTeamStats | Avg| 36ms| 38ms | 2ms | 5.520
| | P99| 50ms| 90ms | 40ms | 80.402
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 15ms | 2ms | 14.912
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 17ms | 4ms | 31.611
| getUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 14ms| 17ms | 3ms | 21.460
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 17ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.642
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| login | Avg| 66ms| 66ms | 0s | 0.000
| | P99| 243ms| 240ms | -3ms | -1.234
| logout | Avg| 28ms| 32ms | 4ms | 14.080
| | P99| 50ms| 179ms | 129ms | 259.757
| patchPost | Avg| 21ms| 18ms | -3ms | -13.957
| | P99| 68ms| 47ms | -21ms | -30.769
| removeUserCustomStatus | Avg| 120ms| 148ms | 28ms | 23.250
| | P99| 381ms| 465ms | 84ms | 22.033
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 6ms| 5ms | -1ms | -18.135
| | P99| 24ms| 26ms | 2ms | 8.462
| searchAllChannels | Avg| 32ms| 33ms | 1ms | 3.117
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 22ms | 3ms | 15.739
| searchPostsInTeam | Avg| 33ms| 48ms | 15ms | 45.109
| | P99| 607ms| 1.484s | 877ms | 144.558
| searchUsers | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 58ms| 71ms | 13ms | 22.243
| setPostReminder | Avg| 14ms| 15ms | 1ms | 7.305
| | P99| 25ms| 84ms | 59ms | 237.425
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.815
| updateCategoriesForTeamForUser | Avg| 52ms| 54ms | 2ms | 3.837
| | P99| 99ms| 197ms | 98ms | 98.776
| updateChannelBookmark | Avg| 43ms| 9ms | -34ms | -79.585
| | P99| 99ms| 25ms | -74ms | -74.748
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 32ms | 8ms | 32.839
| updateReadStateAllThreadsByUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -51.282
| updateReadStateThreadByUser | Avg| 28ms| 25ms | -3ms | -10.651
| | P99| 82ms| 87ms | 5ms | 6.130
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 369ms| 396ms | 27ms | 7.324
| | P99| 979ms| 987ms | 8ms | 0.817
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.311
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 30ms| 36ms | 6ms | 20.204
