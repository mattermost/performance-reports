### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 2ms | 20ms | 18ms | 800.79
| PostStore.AnalyticsPostCount | avg | 240ms | 348ms | 108ms | 45.01
| ProductNoticesStore.ClearOldNotices | avg | 10ms | 13ms | 3ms | 31.29
| ChannelStore.GetTeamChannels | avg | 10ms | 13ms | 3ms | 31.21
| PostStore.SearchPostsForUser | avg | 22ms | 25ms | 3ms | 13.92
| UserStore.GetAllProfilesInChannel | avg | 128ms | 130ms | 2ms | 1.57
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 5ms | 403ms | 398ms | 7966.10
| JobStore.UpdateOptimistically | p99 | 5ms | 14ms | 9ms | 181.82
| JobStore.UpdateStatus | p99 | 5ms | 14ms | 9ms | 181.82
| LinkMetadataStore.Save | p99 | 7ms | 19ms | 12ms | 170.21
| ProductNoticesStore.ClearOldNotices | p99 | 10ms | 25ms | 15ms | 150.75
| ChannelStore.GetTeamChannels | p99 | 10ms | 25ms | 15ms | 150.67
| ChannelBookmarkStore.Save | p99 | 10ms | 24ms | 14ms | 142.13
| RoleStore.GetByNames | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 40ms | 15ms | 60.36
| JobStore.GetAllByStatus | p99 | 5ms | 8ms | 3ms | 60.20
| PostStore.GetPostsAfter | p99 | 5ms | 8ms | 3ms | 60.07
| ChannelStore.SearchGroupChannels | p99 | 15ms | 21ms | 6ms | 39.71
| UserStore.GetByUsername | p99 | 7ms | 9ms | 2ms | 29.57
| UserStore.GetAllProfilesInChannel | p99 | 250ms | 315ms | 65ms | 26.02
| ChannelStore.Save | p99 | 24ms | 27ms | 3ms | 12.67
| ChannelStore.GetByName | p99 | 17ms | 19ms | 2ms | 11.87
| WebhookStore.GetOutgoingByTeam | p99 | 20ms | 22ms | 2ms | 9.84
| ChannelStore.GetMemberCount | p99 | 31ms | 34ms | 3ms | 9.81
| PostStore.GetPostsSince | p99 | 39ms | 41ms | 2ms | 5.07
| ProductNoticesStore.View | p99 | 74ms | 77ms | 3ms | 4.06
| UserStore.AutocompleteUsersInChannel | p99 | 172ms | 177ms | 5ms | 2.90
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -122.02
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -116.38
| TeamStore.AnalyticsTeamCount | avg | 2ms | 0s | -2ms | -114.65
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -112.04
| ChannelBookmarkStore.Delete | avg | 3ms | 0s | -3ms | -105.40
| UserStore.AnalyticsGetInactiveUsersCount | avg | 2ms | 0s | -2ms | -103.92
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -101.55
| ScheduledPostStore.GetScheduledPostsForUser | avg | 2ms | 0s | -2ms | -100.43
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -100.32
| ComplianceStore.MessageExport | avg | 3ms | 0s | -3ms | -99.96
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 55ms | 0s | -55ms | -99.82
| UserStore.AnalyticsActiveCount | avg | 14ms | 0s | -14ms | -99.12
| ChannelStore.AnalyticsTypeCount | avg | 3ms | 0s | -3ms | -97.91
| RetentionPolicyStore.GetAll | avg | 9ms | 0s | -9ms | -95.57
| ChannelStore.GetMembersForUserWithPagination | avg | 6ms | 0s | -6ms | -94.36
| ProductNoticesStore.GetViews | avg | 2ms | 0s | -2ms | -88.78
| EmojiStore.Search | avg | 2ms | 0s | -2ms | -86.11
| ChannelStore.AutocompleteInTeamForSearch | avg | 47ms | 29ms | -18ms | -38.27
| UserStore.GetProfilesInChannel | avg | 85ms | 62ms | -23ms | -26.96
| UserStore.Count | avg | 11ms | 9ms | -2ms | -18.73
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 13ms | 11ms | -2ms | -15.86
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 8ms | 0s | -8ms | -105.26
| RetentionPolicyStore.GetAll | p99 | 25ms | 0s | -25ms | -101.21
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.AnalyticsTypeCount | p99 | 5ms | 0s | -5ms | -100.87
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.73
| ChannelStore.GetMembersForUserWithPagination | p99 | 10ms | 0s | -10ms | -100.68
| UserStore.AnalyticsActiveCount | p99 | 25ms | 0s | -25ms | -100.60
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 100ms | 0s | -100ms | -100.50
| JobStore.GetAllByTypePage | p99 | 9ms | 0s | -9ms | -99.42
| JobStore.UpdateStatusOptimistically | p99 | 23ms | 5ms | -18ms | -78.73
| JobStore.Get | p99 | 20ms | 5ms | -15ms | -74.53
| UserStore.Update | p99 | 17ms | 6ms | -11ms | -66.26
| JobStore.GetNewestJobByStatusesAndType | p99 | 15ms | 5ms | -10ms | -65.57
| UserStore.Count | p99 | 44ms | 24ms | -20ms | -44.94
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -44.94
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 5ms | -4ms | -44.91
| PostStore.GetPostReminderMetadata | p99 | 9ms | 5ms | -4ms | -44.90
| ChannelStore.AutocompleteInTeamForSearch | p99 | 443ms | 248ms | -195ms | -44.06
| ClusterDiscoveryStore.SetLastPingAt | p99 | 14ms | 8ms | -6ms | -43.48
| PostAcknowledgementStore.GetForPost | p99 | 8ms | 5ms | -3ms | -37.15
| JobStore.GetCountByStatusAndType | p99 | 20ms | 14ms | -6ms | -30.50
| FileInfoStore.SetContent | p99 | 15ms | 11ms | -4ms | -26.76
| PreferenceStore.GetAll | p99 | 10ms | 8ms | -2ms | -20.93
| UserStore.UpdateUpdateAt | p99 | 10ms | 8ms | -2ms | -20.39
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 27ms | 25ms | -2ms | -7.35
| PostStore.SearchPostsForUser | p99 | 537ms | 507ms | -30ms | -5.59
| ChannelStore.CreateDirectChannel | p99 | 42ms | 40ms | -2ms | -4.76
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 18ms | 21ms | 3ms | 16.39
| searchPostsInTeam | avg | 28ms | 31ms | 3ms | 10.70
| addChannelMember | avg | 130ms | 141ms | 11ms | 8.46
| removeUserCustomStatus | avg | 85ms | 91ms | 6ms | 7.05
| createDirectChannel | avg | 115ms | 123ms | 8ms | 6.96
| createChannel | avg | 160ms | 167ms | 7ms | 4.36
| login | avg | 54ms | 56ms | 2ms | 3.69
| createUser | avg | 109ms | 111ms | 2ms | 1.83
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 25ms | 49ms | 24ms | 96.58
| getPublicChannelsForTeam | p99 | 25ms | 47ms | 22ms | 88.52
| createDirectChannel | p99 | 247ms | 392ms | 145ms | 58.63
| searchGroupChannels | p99 | 15ms | 21ms | 6ms | 39.71
| autocompleteUsers | p99 | 145ms | 157ms | 12ms | 8.25
| getPostsForChannel | p99 | 99ms | 103ms | 4ms | 4.05
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getProductNotices | avg | 3ms | 0s | -3ms | -118.05
| getUsersByGroupChannelIds | avg | 4ms | 0s | -4ms | -106.99
| getChannelMembersForUser | avg | 7ms | 0s | -7ms | -106.03
| getFilteredUsersStats | avg | 10ms | 0s | -10ms | -103.44
| getTeamScheduledPosts | avg | 4ms | 0s | -4ms | -98.90
| getGroupsAssociatedToChannelsByTeam | avg | 2ms | 0s | -2ms | -97.85
| getJobsByType | avg | 2ms | 0s | -2ms | -95.67
| getUserByUsername | avg | 2ms | 0s | -2ms | -89.88
| getGroups | avg | 2ms | 0s | -2ms | -85.00
| autocompleteEmojis | avg | 2ms | 0s | -2ms | -84.29
| autocompleteChannelsForTeamForSearch | avg | 47ms | 29ms | -18ms | -38.22
| getCategoriesForTeamForUser | avg | 13ms | 11ms | -2ms | -15.72
| createChannelBookmark | avg | 14ms | 12ms | -2ms | -13.93
| patchPost | avg | 22ms | 20ms | -2ms | -9.30
| createGroupChannel | avg | 211ms | 194ms | -17ms | -8.05
| getProfileImage | avg | 82ms | 77ms | -5ms | -6.06
| uploadFileStream | avg | 399ms | 376ms | -23ms | -5.76
| addTeamMember | avg | 441ms | 435ms | -6ms | -1.36
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getGroups | p99 | 5ms | 0s | -5ms | -101.01
| getTeamScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 5ms | 0s | -5ms | -101.01
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| getProductNotices | p99 | 5ms | 0s | -5ms | -101.01
| getRolesByNames | p99 | 5ms | 0s | -5ms | -101.01
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| getUserByUsername | p99 | 5ms | 0s | -5ms | -100.73
| getUsersByGroupChannelIds | p99 | 5ms | 0s | -5ms | -100.73
| getChannelMembersForUser | p99 | 10ms | 0s | -10ms | -100.50
| getFilteredUsersStats | p99 | 10ms | 0s | -10ms | -100.50
| getJobsByType | p99 | 9ms | 0s | -9ms | -99.42
| getChannel | p99 | 22ms | 9ms | -13ms | -59.10
| createChannelBookmark | p99 | 49ms | 25ms | -24ms | -49.23
| autocompleteChannelsForTeamForSearch | p99 | 443ms | 248ms | -195ms | -44.06
| getCategoriesForTeamForUser | p99 | 28ms | 25ms | -3ms | -10.74
| unfollowThreadByUser | p99 | 24ms | 22ms | -2ms | -8.46
| patchPost | p99 | 48ms | 45ms | -3ms | -6.29
| searchPostsInTeam | p99 | 537ms | 507ms | -30ms | -5.59
| getProfileImage | p99 | 364ms | 350ms | -14ms | -3.84
| getFileThumbnail | p99 | 86ms | 84ms | -2ms | -2.34
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.944
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -122.016
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 3ms| 0s | -3ms | -105.400
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -116.382
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 5ms| 6ms | 1ms | 20.160
| |  P99| 10ms| 24ms | 14ms | 142.130
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 55ms| 0s | -55ms | -99.820
| |  P99| 100ms| 0s | -100ms | -100.503
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.138
| ChannelStore.AnalyticsTypeCount |  Avg| 3ms| 0s | -3ms | -97.915
| |  P99| 5ms| 0s | -5ms | -100.872
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 47ms| 29ms | -18ms | -38.267
| |  P99| 443ms| 248ms | -195ms | -44.062
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.762
| ChannelStore.CreateInitialSidebarCategories |  Avg| 11ms| 10ms | -1ms | -9.357
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 90ms| 91ms | 1ms | 1.117
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 11.866
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.072
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.386
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 31ms| 34ms | 3ms | 9.814
| ChannelStore.GetMemberCountsByGroup |  Avg| 1ms| 0s | -1ms | -81.737
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.562
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 0s | -6ms | -94.365
| |  P99| 10ms| 0s | -10ms | -100.683
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 40ms | 15ms | 60.355
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 13ms| 11ms | -2ms | -15.858
| |  P99| 27ms| 25ms | -2ms | -7.353
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 10ms| 13ms | 3ms | 31.205
| |  P99| 10ms| 25ms | 15ms | 150.674
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 27ms | 3ms | 12.674
| ChannelStore.SaveMember |  Avg| 21ms| 20ms | -1ms | -4.839
| |  P99| 47ms| 46ms | -1ms | -2.150
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 39.709
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 21ms| 22ms | 1ms | 4.793
| |  P99| 48ms| 49ms | 1ms | 2.078
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 8ms | -6ms | -43.480
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 0s | -3ms | -99.955
| |  P99| 8ms| 0s | -8ms | -105.263
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 2ms | -1ms | -34.903
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.487
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 1ms | -1ms | -65.389
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 2ms| 0s | -2ms | -86.112
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.103
| FileInfoStore.SetContent |  Avg| 5ms| 4ms | -1ms | -20.759
| |  P99| 15ms| 11ms | -4ms | -26.756
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 0s | -2ms | -100.322
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -74.534
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.202
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -101.547
| |  P99| 9ms| 0s | -9ms | -99.417
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 14ms | -6ms | -30.496
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 5ms | -10ms | -65.574
| JobStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 14ms | 9ms | 181.818
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 14ms | 9ms | 181.818
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 2ms | -1ms | -29.009
| |  P99| 23ms| 5ms | -18ms | -78.732
| LicenseStore.GetAll |  Avg| 1ms| 0s | -1ms | -92.962
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 3ms | 1ms | 40.182
| |  P99| 7ms| 19ms | 12ms | 170.206
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.319
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.153
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.939
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 240ms| 348ms | 108ms | 45.006
| |  P99| 495ms| 498ms | 3ms | 0.606
| PostStore.Delete |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.903
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.192
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.070
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 39ms| 41ms | 2ms | 5.075
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 6ms | -1ms | -15.013
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 22ms| 25ms | 3ms | 13.917
| |  P99| 537ms| 507ms | -30ms | -5.586
| PostStore.SetPostReminder |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 8ms | -1ms | -10.995
| |  P99| 25ms| 24ms | -1ms | -4.005
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.693
| PreferenceStore.GetAll |  Avg| 3ms| 2ms | -1ms | -38.336
| |  P99| 10ms| 8ms | -2ms | -20.927
| PreferenceStore.Save |  Avg| 5ms| 4ms | -1ms | -22.072
| |  P99| 16ms| 16ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 10ms| 13ms | 3ms | 31.295
| |  P99| 10ms| 25ms | 15ms | 150.754
| ProductNoticesStore.GetViews |  Avg| 2ms| 0s | -2ms | -88.778
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 74ms| 77ms | 3ms | 4.059
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.922
| RetentionPolicyStore.GetAll |  Avg| 9ms| 0s | -9ms | -95.567
| |  P99| 25ms| 0s | -25ms | -101.214
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -126.429
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.909
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 0s | -2ms | -100.427
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 2ms | -1ms | -39.139
| |  P99| 5ms| 5ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 2ms| 20ms | 18ms | 800.788
| |  P99| 5ms| 403ms | 398ms | 7966.099
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 0s | -2ms | -114.651
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 35ms | 1ms | 2.945
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 29ms| 30ms | 1ms | 3.497
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.467
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.393
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.037
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 2ms | -1ms | -39.505
| |  P99| 8ms| 7ms | -1ms | -12.019
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.294
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 0s | -14ms | -99.124
| |  P99| 25ms| 0s | -25ms | -100.604
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 0s | -2ms | -103.924
| |  P99| 5ms| 0s | -5ms | -101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 172ms| 177ms | 5ms | 2.900
| UserStore.Count |  Avg| 11ms| 9ms | -2ms | -18.733
| |  P99| 44ms| 24ms | -20ms | -44.944
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 128ms| 130ms | 2ms | 1.565
| |  P99| 250ms| 315ms | 65ms | 26.017
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.575
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -112.044
| |  P99| 5ms| 0s | -5ms | -100.734
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 85ms| 62ms | -23ms | -26.958
| |  P99| 248ms| 247ms | -1ms | -0.403
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.753
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 64ms| 64ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 49ms| 50ms | 1ms | 2.020
| UserStore.Update |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 6ms | -11ms | -66.260
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 2ms | -1ms | -39.763
| |  P99| 9ms| 8ms | -1ms | -11.301
| UserStore.UpdateLastLogin |  Avg| 4ms| 3ms | -1ms | -27.978
| |  P99| 9ms| 8ms | -1ms | -10.988
| UserStore.UpdateUpdateAt |  Avg| 4ms| 3ms | -1ms | -27.180
| |  P99| 10ms| 8ms | -2ms | -20.389
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.840
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 130ms| 141ms | 11ms | 8.455
| | P99| 248ms| 250ms | 2ms | 0.807
| addTeamMember | Avg| 441ms| 435ms | -6ms | -1.360
| | P99| 982ms| 981ms | -1ms | -0.102
| autocompleteChannelsForTeamForSearch | Avg| 47ms| 29ms | -18ms | -38.218
| | P99| 443ms| 248ms | -195ms | -44.062
| autocompleteEmojis | Avg| 2ms| 0s | -2ms | -84.293
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 31ms| 32ms | 1ms | 3.210
| | P99| 145ms| 157ms | 12ms | 8.253
| channelMemberCountsByGroup | Avg| 1ms| 0s | -1ms | -77.057
| | P99| 5ms| 0s | -5ms | -101.010
| createChannel | Avg| 160ms| 167ms | 7ms | 4.363
| | P99| 248ms| 249ms | 1ms | 0.402
| createChannelBookmark | Avg| 14ms| 12ms | -2ms | -13.929
| | P99| 49ms| 25ms | -24ms | -49.231
| createDirectChannel | Avg| 115ms| 123ms | 8ms | 6.964
| | P99| 247ms| 392ms | 145ms | 58.630
| createGroupChannel | Avg| 211ms| 194ms | -17ms | -8.051
| | P99| 493ms| 492ms | -1ms | -0.203
| createPost | Avg| 166ms| 165ms | -1ms | -0.603
| | P99| 490ms| 489ms | -1ms | -0.204
| createUser | Avg| 109ms| 111ms | 2ms | 1.830
| | P99| 247ms| 248ms | 1ms | 0.404
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.671
| deletePost | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 9ms | -1ms | -10.430
| | P99| 24ms| 24ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 13ms| 11ms | -2ms | -15.719
| | P99| 28ms| 25ms | -3ms | -10.744
| getChannel | Avg| 5ms| 4ms | -1ms | -21.483
| | P99| 22ms| 9ms | -13ms | -59.096
| getChannelMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| getChannelMembers | Avg| 3ms| 4ms | 1ms | 29.810
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.467
| getChannelMembersForUser | Avg| 7ms| 0s | -7ms | -106.034
| | P99| 10ms| 0s | -10ms | -100.503
| getChannelStats | Avg| 3ms| 2ms | -1ms | -36.050
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.890
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 95ms| 94ms | -1ms | -1.057
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 86ms| 84ms | -2ms | -2.339
| getFilteredUsersStats | Avg| 10ms| 0s | -10ms | -103.437
| | P99| 10ms| 0s | -10ms | -100.503
| getGroups | Avg| 2ms| 0s | -2ms | -85.000
| | P99| 5ms| 0s | -5ms | -101.010
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 0s | -2ms | -97.847
| | P99| 5ms| 0s | -5ms | -101.010
| getJobsByType | Avg| 2ms| 0s | -2ms | -95.667
| | P99| 9ms| 0s | -9ms | -99.417
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 99ms| 103ms | 4ms | 4.047
| getPostsForChannelAroundLastUnread | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 43ms| 43ms | 0s | 0.000
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.350
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -69.575
| | P99| 5ms| 0s | -5ms | -101.010
| getProductNotices | Avg| 3ms| 0s | -3ms | -118.047
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 82ms| 77ms | -5ms | -6.065
| | P99| 364ms| 350ms | -14ms | -3.843
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 47ms | 22ms | 88.521
| getRolesByNames | Avg| 1ms| 0s | -1ms | -132.052
| | P99| 5ms| 0s | -5ms | -101.010
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 0s | -4ms | -98.902
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamStats | Avg| 34ms| 35ms | 1ms | 2.939
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.052
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getUserByUsername | Avg| 2ms| 0s | -2ms | -89.877
| | P99| 5ms| 0s | -5ms | -100.734
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByGroupChannelIds | Avg| 4ms| 0s | -4ms | -106.994
| | P99| 5ms| 0s | -5ms | -100.734
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 54ms| 56ms | 2ms | 3.691
| | P99| 218ms| 217ms | -1ms | -0.460
| logout | Avg| 18ms| 21ms | 3ms | 16.389
| | P99| 25ms| 49ms | 24ms | 96.579
| patchPost | Avg| 22ms| 20ms | -2ms | -9.299
| | P99| 48ms| 45ms | -3ms | -6.291
| removeUserCustomStatus | Avg| 85ms| 91ms | 6ms | 7.047
| | P99| 246ms| 247ms | 1ms | 0.406
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 8ms | -1ms | -11.757
| | P99| 24ms| 24ms | 0s | 0.000
| searchAllChannels | Avg| 33ms| 34ms | 1ms | 3.007
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 21ms | 6ms | 39.709
| searchPostsInTeam | Avg| 28ms| 31ms | 3ms | 10.697
| | P99| 537ms| 507ms | -30ms | -5.586
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.457
| updateCategoriesForTeamForUser | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.492
| updateReadStateThreadByUser | Avg| 31ms| 30ms | -1ms | -3.266
| | P99| 61ms| 61ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 399ms| 376ms | -23ms | -5.764
| | P99| 990ms| 981ms | -9ms | -0.909
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| viewChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
