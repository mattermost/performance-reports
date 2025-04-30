### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | avg | 22ms | 63ms | 41ms | 184.49
| SessionStore.Remove | avg | 2ms | 5ms | 3ms | 155.69
| PostStore.AnalyticsPostCount | avg | 88ms | 137ms | 49ms | 55.62
| ChannelStore.GetTeamChannels | avg | 10ms | 14ms | 4ms | 39.85
| ChannelStore.AnalyticsCountAll | avg | 17ms | 20ms | 3ms | 17.20
| ChannelStore.AutocompleteInTeamForSearch | avg | 33ms | 38ms | 5ms | 15.13
| ChannelStore.UpdateSidebarCategories | avg | 27ms | 29ms | 2ms | 7.52
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.Remove | p99 | 5ms | 47ms | 42ms | 848.48
| ChannelStore.AutocompleteInTeamForSearch | p99 | 133ms | 830ms | 697ms | 523.90
| RoleStore.GetByNames | p99 | 9ms | 42ms | 33ms | 385.99
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 73ms | 48ms | 193.13
| PostStore.GetPostReminderMetadata | p99 | 9ms | 22ms | 13ms | 139.01
| JobStore.GetAllByStatus | p99 | 10ms | 23ms | 13ms | 130.74
| JobStore.UpdateStatusOptimistically | p99 | 8ms | 18ms | 10ms | 129.03
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 10ms | 22ms | 12ms | 125.33
| ChannelStore.GetMembersForUserWithPagination | p99 | 10ms | 21ms | 11ms | 110.55
| RoleStore.ChannelHigherScopedPermissions | p99 | 20ms | 41ms | 21ms | 103.79
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 10ms | 5ms | 100.90
| PostStore.SearchPostsForUser | p99 | 463ms | 908ms | 445ms | 96.20
| ChannelStore.UpdateSidebarCategories | p99 | 50ms | 92ms | 42ms | 84.79
| LinkMetadataStore.Save | p99 | 5ms | 9ms | 4ms | 80.81
| JobStore.Save | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 97ms | 150ms | 53ms | 54.39
| ChannelStore.GetMember | p99 | 11ms | 17ms | 6ms | 52.89
| ChannelStore.CreateDirectChannel | p99 | 45ms | 67ms | 22ms | 48.71
| StatusStore.UpdateExpiredDNDStatuses | p99 | 21ms | 28ms | 7ms | 34.06
| ThreadStore.MaintainMembership | p99 | 10ms | 13ms | 3ms | 29.06
| UserStore.GetProfileByIds | p99 | 12ms | 15ms | 3ms | 25.95
| DraftStore.Delete | p99 | 8ms | 10ms | 2ms | 24.51
| ChannelStore.GetPinnedPostCount | p99 | 8ms | 10ms | 2ms | 23.56
| FileInfoStore.GetByIds | p99 | 9ms | 11ms | 2ms | 22.98
| UserStore.GetUnreadCount | p99 | 19ms | 23ms | 4ms | 21.57
| ChannelStore.SearchGroupChannels | p99 | 19ms | 22ms | 3ms | 16.04
| TeamStore.GetMember | p99 | 13ms | 15ms | 2ms | 15.00
| FileInfoStore.Save | p99 | 14ms | 16ms | 2ms | 14.03
| ChannelStore.GetMemberForPost | p99 | 15ms | 17ms | 2ms | 13.65
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 15ms | 17ms | 2ms | 13.27
| ThreadStore.GetThreadsForUser | p99 | 15ms | 17ms | 2ms | 13.25
| TeamStore.SaveMember | p99 | 61ms | 69ms | 8ms | 13.19
| SessionStore.GetLRUSessions | p99 | 16ms | 18ms | 2ms | 12.60
| PostStore.Save | p99 | 25ms | 28ms | 3ms | 12.09
| PluginStore.SetWithOptions | p99 | 18ms | 20ms | 2ms | 11.20
| PostAcknowledgementStore.GetForPost | p99 | 19ms | 21ms | 2ms | 10.61
| PostStore.Get | p99 | 19ms | 21ms | 2ms | 10.34
| UserStore.Search | p99 | 50ms | 55ms | 5ms | 10.02
| SessionStore.Get | p99 | 30ms | 33ms | 3ms | 9.99
| WebhookStore.GetOutgoingByTeam | p99 | 34ms | 37ms | 3ms | 8.79
| PreferenceStore.Save | p99 | 35ms | 38ms | 3ms | 8.60
| ChannelStore.GetByName | p99 | 36ms | 39ms | 3ms | 8.44
| ChannelStore.CreateInitialSidebarCategories | p99 | 48ms | 51ms | 3ms | 6.26
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 47ms | 49ms | 2ms | 4.25
| ChannelStore.SaveMember | p99 | 88ms | 90ms | 2ms | 2.28
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -121.06
| ChannelStore.GetMembers | avg | 4ms | 0s | -4ms | -114.26
| TeamStore.GetByName | avg | 2ms | 0s | -2ms | -94.97
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -92.13
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -88.74
| JobStore.GetCountByStatusAndType | avg | 4ms | 2ms | -2ms | -55.41
| ChannelBookmarkStore.Delete | avg | 5ms | 3ms | -2ms | -37.75
| ChannelStore.GetSidebarCategory | avg | 8ms | 6ms | -2ms | -23.62
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetByName | p99 | 5ms | 0s | -5ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.GetCountByStatusAndType | p99 | 71ms | 8ms | -63ms | -89.36
| ClusterDiscoveryStore.SetLastPingAt | p99 | 28ms | 13ms | -15ms | -54.07
| ChannelBookmarkStore.Delete | p99 | 10ms | 5ms | -5ms | -50.25
| UserStore.GetByUsername | p99 | 16ms | 8ms | -8ms | -50.01
| ChannelStore.GetChannelsByUser | p99 | 17ms | 9ms | -8ms | -46.62
| ChannelStore.GetSidebarCategory | p99 | 44ms | 24ms | -20ms | -45.46
| FileInfoStore.AttachToPost | p99 | 18ms | 10ms | -8ms | -45.26
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.72
| UserStore.Count | p99 | 42ms | 25ms | -17ms | -40.23
| PostStore.GetPostsAfter | p99 | 8ms | 5ms | -3ms | -35.50
| JobStore.UpdateOptimistically | p99 | 9ms | 6ms | -3ms | -34.29
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 8ms | -2ms | -20.24
| ChannelStore.GetFileCount | p99 | 10ms | 8ms | -2ms | -20.15
| ThreadStore.GetThreadFollowers | p99 | 13ms | 11ms | -2ms | -15.19
| ChannelStore.Save | p99 | 34ms | 31ms | -3ms | -8.95
| FileInfoStore.SetContent | p99 | 24ms | 22ms | -2ms | -8.38
| UserStore.AutocompleteUsersInChannel | p99 | 181ms | 175ms | -6ms | -3.32
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 30ms | 72ms | 42ms | 138.18
| logout | avg | 23ms | 28ms | 5ms | 21.76
| autocompleteChannelsForTeamForSearch | avg | 33ms | 38ms | 5ms | 15.10
| uploadFileStream | avg | 411ms | 434ms | 23ms | 5.60
| createGroupChannel | avg | 251ms | 265ms | 14ms | 5.59
| createDirectChannel | avg | 164ms | 170ms | 6ms | 3.65
| getProfileImage | avg | 78ms | 80ms | 2ms | 2.58
| createUser | avg | 114ms | 116ms | 2ms | 1.75
| removeUserCustomStatus | avg | 115ms | 117ms | 2ms | 1.74
| createPost | avg | 174ms | 176ms | 2ms | 1.15
| addTeamMember | avg | 579ms | 585ms | 6ms | 1.04
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 133ms | 830ms | 697ms | 523.90
| getPublicChannelsForTeam | p99 | 25ms | 73ms | 48ms | 193.13
| patchPost | p99 | 49ms | 100ms | 51ms | 104.21
| logout | p99 | 49ms | 94ms | 45ms | 92.55
| searchPostsInTeam | p99 | 481ms | 911ms | 430ms | 89.34
| setPostReminder | p99 | 25ms | 47ms | 22ms | 88.53
| updatePreferences | p99 | 10ms | 18ms | 8ms | 80.62
| getPostThread | p99 | 29ms | 42ms | 13ms | 44.41
| getProfileImage | p99 | 325ms | 401ms | 76ms | 23.38
| searchUsers | p99 | 50ms | 59ms | 9ms | 18.01
| searchGroupChannels | p99 | 19ms | 22ms | 3ms | 15.54
| getClientConfig | p99 | 24ms | 27ms | 3ms | 12.29
| saveReaction | p99 | 36ms | 40ms | 4ms | 11.18
| addTeamMember | p99 | 1.822s | 2.023s | 201ms | 11.03
| getPostsForChannelAroundLastUnread | p99 | 67ms | 72ms | 5ms | 7.43
| unfollowThreadByUser | p99 | 79ms | 83ms | 4ms | 5.03
| getChannelMember | p99 | 42ms | 44ms | 2ms | 4.79
| getCategoriesForTeamForUser | p99 | 47ms | 49ms | 2ms | 4.21
| getPostsForChannel | p99 | 190ms | 197ms | 7ms | 3.68
| createUser | p99 | 289ms | 294ms | 5ms | 1.73
| createPost | p99 | 777ms | 788ms | 11ms | 1.42
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 3ms | 0s | -3ms | -113.42
| getChannelByNameForTeamName | avg | 5ms | 0s | -5ms | -110.33
| getChannelMembers | avg | 4ms | 0s | -4ms | -102.22
| deleteChannelBookmark | avg | 12ms | 0s | -12ms | -96.46
| getUsersByGroupChannelIds | avg | 4ms | 0s | -4ms | -91.41
| getJobsByType | avg | 2ms | 0s | -2ms | -84.00
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -82.91
| createChannelBookmark | avg | 19ms | 11ms | -8ms | -41.57
| getFilteredUsersStats | avg | 15ms | 11ms | -4ms | -26.62
| createChannel | avg | 204ms | 195ms | -9ms | -4.42
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getChannelByNameForTeamName | p99 | 5ms | 0s | -5ms | -101.01
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getJobsByType | p99 | 5ms | 0s | -5ms | -101.01
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -100.90
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| getChannelUnread | p99 | 10ms | 5ms | -5ms | -52.45
| getFilteredUsersStats | p99 | 49ms | 25ms | -24ms | -48.98
| getAnalytics | p99 | 96ms | 50ms | -46ms | -47.90
| getChannelsForUser | p99 | 42ms | 23ms | -19ms | -44.97
| createSchedulePost | p99 | 9ms | 5ms | -4ms | -44.65
| getDrafts | p99 | 12ms | 10ms | -2ms | -16.11
| autocompleteUsers | p99 | 160ms | 149ms | -11ms | -6.88
| updateCategoriesForTeamForUser | p99 | 98ms | 96ms | -2ms | -2.04
| createDirectChannel | p99 | 469ms | 462ms | -7ms | -1.49
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| BotStore.Get |  Avg| 3ms| 2ms | -1ms | -35.806
| |  P99| 9ms| 5ms | -4ms | -43.716
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -92.134
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 5ms| 3ms | -2ms | -37.753
| |  P99| 10ms| 5ms | -5ms | -50.251
| ChannelBookmarkStore.Get |  Avg| 2ms| 3ms | 1ms | 42.678
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 7ms| 6ms | -1ms | -14.547
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 17ms| 20ms | 3ms | 17.196
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 34ms | 1ms | 3.063
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 33ms| 38ms | 5ms | 15.132
| |  P99| 133ms| 830ms | 697ms | 523.903
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 45ms| 67ms | 22ms | 48.707
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 48ms| 51ms | 3ms | 6.258
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.905
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.272
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 97ms| 150ms | 53ms | 54.391
| ChannelStore.GetByName |  Avg| 4ms| 5ms | 1ms | 22.376
| |  P99| 36ms| 39ms | 3ms | 8.440
| ChannelStore.GetByNameIncludeDeleted |  Avg| 3ms| 2ms | -1ms | -36.398
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.515
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 9ms | -8ms | -46.622
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.700
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.151
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.590
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 17ms | 6ms | 52.892
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.652
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 4ms| 0s | -4ms | -114.263
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 7ms | 1ms | 15.591
| |  P99| 10ms| 21ms | 11ms | 110.553
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.560
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 14ms | 1ms | 7.560
| |  P99| 25ms| 73ms | 48ms | 193.129
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.254
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 6ms | -2ms | -23.624
| |  P99| 44ms| 24ms | -20ms | -45.457
| ChannelStore.GetTeamChannels |  Avg| 10ms| 14ms | 4ms | 39.852
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.451
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.541
| ChannelStore.Save |  Avg| 9ms| 8ms | -1ms | -11.368
| |  P99| 34ms| 31ms | -3ms | -8.954
| ChannelStore.SaveMember |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.277
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 16.042
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 27ms| 29ms | 2ms | 7.523
| |  P99| 50ms| 92ms | 42ms | 84.795
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 13ms | -15ms | -54.065
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.507
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.510
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.455
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -45.261
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 22.984
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.311
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.035
| FileInfoStore.SetContent |  Avg| 6ms| 5ms | -1ms | -18.088
| |  P99| 24ms| 22ms | -2ms | -8.382
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.271
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.147
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.349
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 3ms | 1ms | 41.749
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 130.735
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -88.740
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 4ms| 2ms | -2ms | -55.414
| |  P99| 71ms| 8ms | -63ms | -89.362
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.236
| JobStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 6ms | -3ms | -34.287
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 129.032
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.929
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.879
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 3ms| 2ms | -1ms | -36.076
| |  P99| 9ms| 8ms | -1ms | -10.989
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.203
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.613
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.648
| PostPriorityStore.GetForPost |  Avg| 3ms| 2ms | -1ms | -39.525
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 88ms| 137ms | 49ms | 55.620
| |  P99| 493ms| 495ms | 2ms | 0.406
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.088
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.343
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 22ms | 13ms | 139.006
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.504
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 12.094
| PostStore.SearchPostsForUser |  Avg| 22ms| 63ms | 41ms | 184.486
| |  P99| 463ms| 908ms | 445ms | 96.203
| PostStore.SetPostReminder |  Avg| 5ms| 4ms | -1ms | -21.777
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.476
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.406
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 35ms| 38ms | 3ms | 8.595
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 91ms| 92ms | 1ms | 1.095
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -121.060
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 41ms | 21ms | 103.788
| RoleStore.GetByNames |  Avg| 3ms| 4ms | 1ms | 38.755
| |  P99| 9ms| 42ms | 33ms | 385.992
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 125.326
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 33ms | 3ms | 9.993
| SessionStore.GetLRUSessions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.604
| SessionStore.GetSessionsExpired |  Avg| 2ms| 3ms | 1ms | 44.066
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 5ms | 3ms | 155.689
| |  P99| 5ms| 47ms | 42ms | 848.485
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 16ms | -1ms | -5.763
| StatusStore.GetByIds |  Avg| 2ms| 3ms | 1ms | 41.273
| |  P99| 8ms| 9ms | 1ms | 12.910
| StatusStore.SaveOrUpdate |  Avg| 13ms| 14ms | 1ms | 7.491
| |  P99| 240ms| 242ms | 2ms | 0.834
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 28ms | 7ms | 34.063
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.670
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 37ms| 36ms | -1ms | -2.739
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.273
| TeamStore.GetByName |  Avg| 2ms| 0s | -2ms | -94.973
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.001
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.175
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.119
| TeamStore.GetTotalMemberCount |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 61ms| 69ms | 8ms | 13.186
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.195
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.251
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.429
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.113
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.781
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 29.065
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 2ms | 1ms | 68.170
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 1ms| 0s | -1ms | -101.473
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.533
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 38ms| 37ms | -1ms | -2.645
| |  P99| 181ms| 175ms | -6ms | -3.324
| UserStore.Count |  Avg| 12ms| 11ms | -1ms | -8.668
| |  P99| 42ms| 25ms | -17ms | -40.233
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.281
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 153ms| 153ms | 0s | 0.000
| |  P99| 474ms| 474ms | 0s | 0.000
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 8ms | -8ms | -50.014
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 5ms | 1ms | 24.495
| |  P99| 5ms| 10ms | 5ms | 100.897
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.946
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.GetUnreadCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 23ms | 4ms | 21.569
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.Save |  Avg| 69ms| 69ms | 0s | 0.000
| |  P99| 194ms| 194ms | 0s | 0.000
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 50ms| 55ms | 5ms | 10.022
| UserStore.Update |  Avg| 5ms| 4ms | -1ms | -21.729
| |  P99| 10ms| 9ms | -1ms | -10.298
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.613
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 37ms | 3ms | 8.793
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 174ms| 174ms | 0s | 0.000
| | P99| 465ms| 468ms | 3ms | 0.645
| addTeamMember | Avg| 579ms| 585ms | 6ms | 1.035
| | P99| 1.822s| 2.023s | 201ms | 11.031
| autocompleteChannelsForTeamForSearch | Avg| 33ms| 38ms | 5ms | 15.104
| | P99| 133ms| 830ms | 697ms | 523.903
| autocompleteUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 160ms| 149ms | -11ms | -6.876
| createChannel | Avg| 204ms| 195ms | -9ms | -4.419
| | P99| 249ms| 248ms | -1ms | -0.402
| createChannelBookmark | Avg| 19ms| 11ms | -8ms | -41.566
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 164ms| 170ms | 6ms | 3.653
| | P99| 469ms| 462ms | -7ms | -1.491
| createGroupChannel | Avg| 251ms| 265ms | 14ms | 5.585
| | P99| 495ms| 496ms | 1ms | 0.202
| createPost | Avg| 174ms| 176ms | 2ms | 1.146
| | P99| 777ms| 788ms | 11ms | 1.416
| createSchedulePost | Avg| 3ms| 2ms | -1ms | -35.178
| | P99| 9ms| 5ms | -4ms | -44.651
| createUser | Avg| 114ms| 116ms | 2ms | 1.754
| | P99| 289ms| 294ms | 5ms | 1.728
| deleteChannelBookmark | Avg| 12ms| 0s | -12ms | -96.456
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 11ms | 1ms | 9.834
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.735
| getAnalytics | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 96ms| 50ms | -46ms | -47.897
| getCategoriesForTeamForUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 47ms| 49ms | 2ms | 4.215
| getChannel | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.061
| getChannelByNameForTeamName | Avg| 5ms| 0s | -5ms | -110.330
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMember | Avg| 6ms| 7ms | 1ms | 15.735
| | P99| 42ms| 44ms | 2ms | 4.794
| getChannelMembers | Avg| 4ms| 0s | -4ms | -102.215
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 18ms| 19ms | 1ms | 5.567
| getChannelMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 31ms | 0s | 0.000
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -52.447
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getChannelsForUser | Avg| 5ms| 4ms | -1ms | -20.291
| | P99| 42ms| 23ms | -19ms | -44.969
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 27ms | 3ms | 12.290
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 10ms | -2ms | -16.106
| getFilePreview | Avg| 39ms| 40ms | 1ms | 2.561
| | P99| 97ms| 98ms | 1ms | 1.032
| getFileThumbnail | Avg| 32ms| 33ms | 1ms | 3.091
| | P99| 90ms| 91ms | 1ms | 1.111
| getFilteredUsersStats | Avg| 15ms| 11ms | -4ms | -26.623
| | P99| 49ms| 25ms | -24ms | -48.979
| getGroups | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -82.913
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -84.000
| | P99| 5ms| 0s | -5ms | -101.010
| getPostThread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 29ms| 42ms | 13ms | 44.408
| getPostsForChannel | Avg| 22ms| 23ms | 1ms | 4.472
| | P99| 190ms| 197ms | 7ms | 3.684
| getPostsForChannelAroundLastUnread | Avg| 17ms| 18ms | 1ms | 5.736
| | P99| 67ms| 72ms | 5ms | 7.433
| getPreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 3ms| 0s | -3ms | -113.417
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 78ms| 80ms | 2ms | 2.580
| | P99| 325ms| 401ms | 76ms | 23.382
| getPublicChannelsForTeam | Avg| 14ms| 15ms | 1ms | 7.053
| | P99| 25ms| 73ms | 48ms | 193.129
| getRolesByNames | Avg| 1ms| 2ms | 1ms | 105.694
| | P99| 10ms| 10ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 1ms | -1ms | -66.321
| | P99| 8ms| 7ms | -1ms | -11.799
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.401
| getTeamScheduledPosts | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getTeamStats | Avg| 37ms| 36ms | -1ms | -2.732
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.147
| getTeamsUnreadForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.351
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.620
| getUserByUsername | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.564
| getUsersByGroupChannelIds | Avg| 4ms| 0s | -4ms | -91.413
| | P99| 5ms| 0s | -5ms | -100.897
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 11ms | 1ms | 10.232
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| login | Avg| 55ms| 55ms | 0s | 0.000
| | P99| 240ms| 241ms | 1ms | 0.416
| logout | Avg| 23ms| 28ms | 5ms | 21.763
| | P99| 49ms| 94ms | 45ms | 92.545
| patchPost | Avg| 24ms| 25ms | 1ms | 4.240
| | P99| 49ms| 100ms | 51ms | 104.215
| removeUserCustomStatus | Avg| 115ms| 117ms | 2ms | 1.737
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 11ms | 1ms | 9.626
| | P99| 36ms| 40ms | 4ms | 11.184
| searchAllChannels | Avg| 33ms| 34ms | 1ms | 3.042
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 22ms | 3ms | 15.544
| searchPostsInTeam | Avg| 30ms| 72ms | 42ms | 138.179
| | P99| 481ms| 911ms | 430ms | 89.345
| searchUsers | Avg| 28ms| 29ms | 1ms | 3.510
| | P99| 50ms| 59ms | 9ms | 18.008
| setPostReminder | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 47ms | 22ms | 88.531
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 79ms| 83ms | 4ms | 5.032
| updateCategoriesForTeamForUser | Avg| 44ms| 43ms | -1ms | -2.281
| | P99| 98ms| 96ms | -2ms | -2.044
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 18ms | 8ms | 80.619
| updateReadStateAllThreadsByUser | Avg| 1ms| 0s | -1ms | -91.536
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 97ms| 97ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 411ms| 434ms | 23ms | 5.602
| | P99| 992ms| 991ms | -1ms | -0.101
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 15ms | 0s | 0.000
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 41ms| 42ms | 1ms | 2.412
