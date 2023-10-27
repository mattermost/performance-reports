### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | avg | 1ms | 8ms | 7ms | 888.73
| ChannelStore.UpdateSidebarCategories | avg | 43ms | 86ms | 43ms | 99.60
| ChannelStore.AutocompleteInTeamForSearch | avg | 30ms | 56ms | 26ms | 87.50
| PostStore.GetPostReminders | avg | 5ms | 9ms | 4ms | 77.64
| PostStore.SetPostReminder | avg | 5ms | 7ms | 2ms | 39.00
| ChannelStore.GetMembersForUserWithPagination | avg | 13ms | 18ms | 5ms | 37.45
| ChannelStore.CreateSidebarCategory | avg | 20ms | 27ms | 7ms | 34.41
| PostStore.Delete | avg | 12ms | 15ms | 3ms | 24.26
| UserStore.AnalyticsActiveCount | avg | 18ms | 20ms | 2ms | 11.32
| PostStore.SearchPostsForUser | avg | 174ms | 179ms | 5ms | 2.88
| UserStore.GetProfilesInChannel | avg | 166ms | 169ms | 3ms | 1.81
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 48ms | 43ms | 868.69
| BotStore.Get | p99 | 10ms | 45ms | 35ms | 366.49
| PostStore.GetPostReminders | p99 | 22ms | 92ms | 70ms | 311.80
| JobStore.Get | p99 | 18ms | 57ms | 39ms | 217.27
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 25ms | 15ms | 150.39
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 141.21
| PostPersistentNotificationStore.Get | p99 | 9ms | 21ms | 12ms | 140.35
| PostPersistentNotificationStore.DeleteExpired | p99 | 9ms | 21ms | 12ms | 140.35
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 20ms | 11ms | 125.71
| ChannelStore.UpdateSidebarCategories | p99 | 213ms | 469ms | 256ms | 120.47
| PostStore.Delete | p99 | 46ms | 95ms | 49ms | 107.48
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 50ms | 25ms | 100.60
| ChannelStore.GetMembersForUserWithPagination | p99 | 25ms | 49ms | 24ms | 96.90
| ChannelStore.GetTeamChannels | p99 | 25ms | 49ms | 24ms | 96.54
| UserStore.AnalyticsActiveCount | p99 | 25ms | 49ms | 24ms | 96.30
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.77
| TeamStore.GetByName | p99 | 24ms | 41ms | 17ms | 71.88
| UserStore.GetByUsername | p99 | 21ms | 34ms | 13ms | 61.79
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 8ms | 3ms | 58.82
| UserStore.Count | p99 | 25ms | 38ms | 13ms | 52.34
| ChannelStore.Autocomplete | p99 | 100ms | 129ms | 29ms | 29.06
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 14ms | 17ms | 3ms | 21.41
| ChannelStore.AutocompleteInTeamForSearch | p99 | 210ms | 248ms | 38ms | 18.11
| JobStore.UpdateOptimistically | p99 | 18ms | 21ms | 3ms | 16.71
| LinkMetadataStore.Save | p99 | 20ms | 23ms | 3ms | 15.19
| JobStore.GetCountByStatusAndType | p99 | 38ms | 43ms | 5ms | 13.25
| ClusterDiscoveryStore.SetLastPingAt | p99 | 41ms | 46ms | 5ms | 12.17
| RoleStore.ChannelHigherScopedPermissions | p99 | 22ms | 24ms | 2ms | 9.18
| UserStore.AutocompleteUsersInChannel | p99 | 296ms | 314ms | 18ms | 6.08
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Upsert | avg | 3ms | 0s | -3ms | -107.15
| StatusStore.SaveOrUpdate | avg | 64ms | 4ms | -60ms | -93.84
| SessionStore.GetSessionsExpired | avg | 3ms | 1ms | -2ms | -78.05
| PluginStore.List | avg | 4ms | 2ms | -2ms | -56.57
| StatusStore.UpdateExpiredDNDStatuses | avg | 4ms | 2ms | -2ms | -52.66
| PostStore.AnalyticsPostCount | avg | 442ms | 223ms | -219ms | -49.54
| PreferenceStore.DeleteCategoryAndName | avg | 6ms | 4ms | -2ms | -33.11
| ChannelStore.CreateDirectChannel | avg | 21ms | 17ms | -4ms | -18.83
| ChannelStore.GetPublicChannelsForTeam | avg | 21ms | 19ms | -2ms | -9.61
| ChannelStore.GetMembers | avg | 138ms | 127ms | -11ms | -7.94
| ProductNoticesStore.View | avg | 48ms | 46ms | -2ms | -4.16
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.19
| StatusStore.SaveOrUpdate | p99 | 809ms | 37ms | -772ms | -95.48
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 9ms | -37ms | -80.87
| SessionStore.Remove | p99 | 22ms | 5ms | -17ms | -78.28
| UserAccessTokenStore.GetByToken | p99 | 22ms | 5ms | -17ms | -77.27
| PostStore.GetPostsAfter | p99 | 18ms | 5ms | -13ms | -71.83
| JobStore.UpdateStatus | p99 | 21ms | 8ms | -13ms | -60.54
| ChannelStore.CreateDirectChannel | p99 | 177ms | 85ms | -92ms | -51.98
| ChannelStore.GetChannelUnread | p99 | 17ms | 8ms | -9ms | -51.88
| SessionStore.GetSessionsExpired | p99 | 10ms | 5ms | -5ms | -51.81
| ChannelStore.Save | p99 | 131ms | 63ms | -68ms | -51.71
| PreferenceStore.DeleteCategoryAndName | p99 | 48ms | 24ms | -24ms | -50.26
| PluginStore.List | p99 | 80ms | 40ms | -40ms | -49.69
| ThreadStore.Get | p99 | 9ms | 5ms | -4ms | -46.92
| ChannelStore.GetPublicChannelsForTeam | p99 | 90ms | 49ms | -41ms | -45.42
| UserStore.GetMany | p99 | 9ms | 5ms | -4ms | -42.78
| PostStore.Update | p99 | 165ms | 97ms | -68ms | -41.34
| FileInfoStore.SetContent | p99 | 68ms | 41ms | -27ms | -39.65
| JobStore.GetAllByStatus | p99 | 66ms | 43ms | -23ms | -35.02
| UserStore.Update | p99 | 68ms | 48ms | -20ms | -29.63
| PluginStore.SetWithOptions | p99 | 69ms | 50ms | -19ms | -27.41
| ChannelStore.GetFileCount | p99 | 37ms | 27ms | -10ms | -26.73
| PostStore.GetSingle | p99 | 24ms | 18ms | -6ms | -25.09
| PostPriorityStore.GetForPost | p99 | 57ms | 43ms | -14ms | -24.67
| PreferenceStore.Save | p99 | 126ms | 95ms | -31ms | -24.56
| ChannelStore.GetMember | p99 | 21ms | 16ms | -5ms | -24.25
| JobStore.Save | p99 | 23ms | 18ms | -5ms | -22.12
| TeamStore.Get | p99 | 24ms | 19ms | -5ms | -20.97
| LinkMetadataStore.Get | p99 | 25ms | 20ms | -5ms | -20.02
| PluginStore.Delete | p99 | 32ms | 26ms | -6ms | -18.54
| PostStore.GetPostIdBeforeTime | p99 | 30ms | 25ms | -5ms | -16.79
| UserStore.GetUnreadCount | p99 | 36ms | 30ms | -6ms | -16.47
| ChannelStore.Get | p99 | 39ms | 33ms | -6ms | -15.42
| ChannelStore.GetMembers | p99 | 548ms | 466ms | -82ms | -14.96
| PostStore.GetPostIdAfterTime | p99 | 41ms | 35ms | -6ms | -14.61
| StatusStore.Get | p99 | 43ms | 37ms | -6ms | -14.01
| StatusStore.GetByIds | p99 | 23ms | 20ms | -3ms | -13.32
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 23ms | 20ms | -3ms | -13.09
| ChannelStore.UpdateLastViewedAt | p99 | 32ms | 28ms | -4ms | -12.67
| SessionStore.Save | p99 | 79ms | 69ms | -10ms | -12.65
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 123ms | 108ms | -15ms | -12.19
| ChannelStore.GetChannelsByUser | p99 | 25ms | 22ms | -3ms | -12.17
| UserStore.GetAllProfiles | p99 | 35ms | 31ms | -4ms | -11.46
| ReactionStore.GetForPost | p99 | 26ms | 23ms | -3ms | -11.45
| PostAcknowledgementStore.GetForPosts | p99 | 36ms | 32ms | -4ms | -11.22
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 37ms | 33ms | -4ms | -10.77
| TeamStore.SaveMember | p99 | 189ms | 170ms | -19ms | -10.07
| ProductNoticesStore.View | p99 | 404ms | 364ms | -40ms | -9.91
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 31ms | 28ms | -3ms | -9.54
| GroupStore.GetGroups | p99 | 32ms | 29ms | -3ms | -9.34
| UserStore.Get | p99 | 22ms | 20ms | -2ms | -8.90
| UserStore.GetProfilesByUsernames | p99 | 34ms | 31ms | -3ms | -8.90
| JobStore.UpdateStatusOptimistically | p99 | 23ms | 21ms | -2ms | -8.83
| UserStore.IsEmpty | p99 | 24ms | 22ms | -2ms | -8.42
| ChannelStore.SearchGroupChannels | p99 | 38ms | 35ms | -3ms | -7.94
| PostPriorityStore.GetForPosts | p99 | 39ms | 36ms | -3ms | -7.79
| SessionStore.UpdateLastActivityAt | p99 | 26ms | 24ms | -2ms | -7.74
| ThreadStore.GetThreadsForUser | p99 | 40ms | 37ms | -3ms | -7.58
| SystemStore.GetByName | p99 | 43ms | 40ms | -3ms | -7.05
| GroupStore.GetByName | p99 | 45ms | 42ms | -3ms | -6.64
| FileInfoStore.AttachToPost | p99 | 50ms | 47ms | -3ms | -6.05
| PostStore.Get | p99 | 50ms | 47ms | -3ms | -6.00
| PreferenceStore.Get | p99 | 36ms | 34ms | -2ms | -5.59
| ChannelStore.IncrementMentionCount | p99 | 38ms | 36ms | -2ms | -5.32
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 38ms | 36ms | -2ms | -5.29
| ChannelStore.GetPinnedPostCount | p99 | 38ms | 36ms | -2ms | -5.23
| UserStore.UpdateUpdateAt | p99 | 39ms | 37ms | -2ms | -5.18
| PostStore.GetPostsBefore | p99 | 39ms | 37ms | -2ms | -5.15
| ChannelStore.GetChannels | p99 | 39ms | 37ms | -2ms | -5.08
| ChannelStore.GetMembersForUser | p99 | 40ms | 38ms | -2ms | -4.94
| ThreadStore.GetTotalUnreadMentions | p99 | 42ms | 40ms | -2ms | -4.79
| PostStore.GetEtag | p99 | 42ms | 40ms | -2ms | -4.72
| TeamStore.GetAllPage | p99 | 44ms | 42ms | -2ms | -4.53
| TeamStore.GetTeamsByUserId | p99 | 44ms | 42ms | -2ms | -4.53
| TeamStore.GetTeamsForUser | p99 | 44ms | 42ms | -2ms | -4.53
| PostStore.GetPosts | p99 | 45ms | 43ms | -2ms | -4.40
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 183ms | 175ms | -8ms | -4.38
| UserStore.UpdateFailedPasswordAttempts | p99 | 46ms | 44ms | -2ms | -4.32
| ThreadStore.MaintainMembership | p99 | 48ms | 46ms | -2ms | -4.21
| ChannelStore.GetByName | p99 | 49ms | 47ms | -2ms | -4.10
| PostStore.Save | p99 | 92ms | 89ms | -3ms | -3.25
| ChannelStore.GetMemberCount | p99 | 94ms | 91ms | -3ms | -3.20
| ChannelStore.CreateInitialSidebarCategories | p99 | 223ms | 216ms | -7ms | -3.14
| ChannelStore.SaveMember | p99 | 239ms | 232ms | -7ms | -2.92
| ReactionStore.Save | p99 | 83ms | 81ms | -2ms | -2.42
| SessionStore.Get | p99 | 87ms | 85ms | -2ms | -2.29
| UserStore.Save | p99 | 239ms | 236ms | -3ms | -1.25
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getLicenseSelfServeStatus | avg | 18ms | 70ms | 52ms | 285.94
| deleteDraft | avg | 1ms | 3ms | 2ms | 209.76
| patchPost | avg | 125ms | 271ms | 146ms | 117.03
| deletePost | avg | 18ms | 36ms | 18ms | 97.35
| autocompleteChannelsForTeamForSearch | avg | 30ms | 56ms | 26ms | 87.32
| updateCategoriesForTeamForUser | avg | 64ms | 107ms | 43ms | 66.93
| getChannelMembers | avg | 4ms | 6ms | 2ms | 44.66
| createCategoryForTeamForUser | avg | 22ms | 28ms | 6ms | 27.67
| getChannelMembersForUser | avg | 11ms | 13ms | 2ms | 18.44
| getPostsForChannelAroundLastUnread | avg | 28ms | 32ms | 4ms | 14.41
| logout | avg | 49ms | 54ms | 5ms | 10.15
| removeUserCustomStatus | avg | 197ms | 212ms | 15ms | 7.60
| searchPostsInTeam | avg | 181ms | 189ms | 8ms | 4.42
| updateUserCustomStatus | avg | 204ms | 213ms | 9ms | 4.40
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 25ms | 92ms | 67ms | 269.94
| deletePost | p99 | 91ms | 242ms | 151ms | 165.61
| getLicenseSelfServeStatus | p99 | 99ms | 245ms | 146ms | 148.22
| updateCategoriesForTeamForUser | p99 | 213ms | 488ms | 275ms | 129.41
| getChannelMembers | p99 | 5ms | 10ms | 5ms | 101.01
| createCategoryForTeamForUser | p99 | 25ms | 50ms | 25ms | 100.60
| createChannel | p99 | 25ms | 49ms | 24ms | 96.54
| patchPost | p99 | 484ms | 905ms | 421ms | 87.03
| getPostsForChannelAroundLastUnread | p99 | 283ms | 475ms | 192ms | 67.81
| searchAllChannels | p99 | 100ms | 129ms | 29ms | 29.06
| getUsers | p99 | 136ms | 162ms | 26ms | 19.15
| autocompleteChannelsForTeamForSearch | p99 | 210ms | 248ms | 38ms | 18.11
| addChannelMember | p99 | 700ms | 803ms | 103ms | 14.71
| getChannelsForUser | p99 | 127ms | 145ms | 18ms | 14.17
| getChannelUnread | p99 | 17ms | 19ms | 2ms | 11.53
| getTeamMember | p99 | 39ms | 42ms | 3ms | 7.63
| autocompleteUsers | p99 | 239ms | 251ms | 12ms | 5.03
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| upsertDraft | avg | 4ms | 0s | -4ms | -102.55
| getFilteredUsersStats | avg | 20ms | 15ms | -5ms | -25.49
| getAnalytics | avg | 31ms | 24ms | -7ms | -22.57
| getPublicChannelsForTeam | avg | 22ms | 20ms | -2ms | -9.00
| createGroupChannel | avg | 431ms | 401ms | -30ms | -6.97
| createPost | avg | 505ms | 479ms | -26ms | -5.15
| getProfileImage | avg | 103ms | 98ms | -5ms | -4.84
| createDirectChannel | avg | 269ms | 261ms | -8ms | -2.98
| uploadFileStream | avg | 469ms | 457ms | -12ms | -2.56
| addChannelMember | avg | 273ms | 267ms | -6ms | -2.20
| addTeamMember | avg | 968ms | 947ms | -21ms | -2.17
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| upsertDraft | p99 | 5ms | 0s | -5ms | -100.19
| getChannel | p99 | 83ms | 32ms | -51ms | -61.82
| logout | p99 | 217ms | 99ms | -118ms | -54.34
| createGroupChannel | p99 | 2.105s | 972ms | -1.133s | -53.82
| getRolesByNames | p99 | 10ms | 5ms | -5ms | -51.28
| setPostReminder | p99 | 47ms | 25ms | -22ms | -47.29
| getPublicChannelsForTeam | p99 | 90ms | 50ms | -40ms | -44.32
| removeUserCustomStatus | p99 | 685ms | 492ms | -193ms | -28.17
| updateUserCustomStatus | p99 | 680ms | 493ms | -187ms | -27.50
| createDirectChannel | p99 | 663ms | 496ms | -167ms | -25.21
| getChannelMember | p99 | 127ms | 100ms | -27ms | -21.22
| addTeamMember | p99 | 4.212s | 3.59s | -622ms | -14.77
| uploadFileStream | p99 | 1.94s | 1.655s | -285ms | -14.69
| getClientConfig | p99 | 110ms | 95ms | -15ms | -13.61
| getFileThumbnail | p99 | 158ms | 139ms | -19ms | -12.01
| getCategoriesForTeamForUser | p99 | 133ms | 118ms | -15ms | -11.26
| getTeamMembersForUser | p99 | 63ms | 57ms | -6ms | -9.48
| getUsersByNames | p99 | 35ms | 32ms | -3ms | -8.68
| searchGroupChannels | p99 | 38ms | 35ms | -3ms | -7.81
| viewChannel | p99 | 104ms | 96ms | -8ms | -7.69
| getTeamsForUser | p99 | 45ms | 42ms | -3ms | -6.72
| getChannelStats | p99 | 78ms | 73ms | -5ms | -6.42
| getTeamsUnreadForUser | p99 | 80ms | 75ms | -5ms | -6.26
| createUser | p99 | 461ms | 436ms | -25ms | -5.42
| getPostsForChannel | p99 | 246ms | 234ms | -12ms | -4.89
| getChannelsForTeamForUser | p99 | 46ms | 44ms | -2ms | -4.39
| getPreferences | p99 | 50ms | 48ms | -2ms | -4.04
| updateReadStateThreadByUser | p99 | 212ms | 204ms | -8ms | -3.78
| getPostThread | p99 | 97ms | 94ms | -3ms | -3.09
| login | p99 | 496ms | 483ms | -13ms | -2.62
| getFilePreview | p99 | 226ms | 221ms | -5ms | -2.21
| createPost | p99 | 2.514s | 2.475s | -39ms | -1.55
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.208
| BotStore.Get |  Avg| 2ms| 3ms | 1ms | 44.081
| |  P99| 10ms| 45ms | 35ms | 366.492
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 33ms | -4ms | -10.772
| ChannelStore.AnalyticsTypeCount |  Avg| 8ms| 9ms | 1ms | 12.694
| |  P99| 10ms| 25ms | 15ms | 150.395
| ChannelStore.Autocomplete |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 100ms| 129ms | 29ms | 29.061
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 30ms| 56ms | 26ms | 87.495
| |  P99| 210ms| 248ms | 38ms | 18.106
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 17ms | -4ms | -18.830
| |  P99| 177ms| 85ms | -92ms | -51.976
| ChannelStore.CreateInitialSidebarCategories |  Avg| 25ms| 24ms | -1ms | -3.976
| |  P99| 223ms| 216ms | -7ms | -3.141
| ChannelStore.CreateSidebarCategory |  Avg| 20ms| 27ms | 7ms | 34.410
| |  P99| 25ms| 50ms | 25ms | 100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 39ms| 33ms | -6ms | -15.415
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 183ms| 175ms | -8ms | -4.375
| ChannelStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 47ms | -2ms | -4.096
| ChannelStore.GetChannelUnread |  Avg| 2ms| 1ms | -1ms | -63.783
| |  P99| 17ms| 8ms | -9ms | -51.876
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 37ms | -2ms | -5.084
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 3ms | -1ms | -27.824
| |  P99| 25ms| 22ms | -3ms | -12.167
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 31ms| 28ms | -3ms | -9.536
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 27ms | -10ms | -26.726
| ChannelStore.GetGuestCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.250
| ChannelStore.GetMemberCount |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 94ms| 91ms | -3ms | -3.204
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.096
| ChannelStore.GetMembers |  Avg| 138ms| 127ms | -11ms | -7.945
| |  P99| 548ms| 466ms | -82ms | -14.955
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 38ms | -2ms | -4.944
| ChannelStore.GetMembersForUserWithPagination |  Avg| 13ms| 18ms | 5ms | 37.446
| |  P99| 25ms| 49ms | 24ms | 96.904
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.232
| ChannelStore.GetPublicChannelsForTeam |  Avg| 21ms| 19ms | -2ms | -9.610
| |  P99| 90ms| 49ms | -41ms | -45.425
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 19ms| 18ms | -1ms | -5.249
| |  P99| 123ms| 108ms | -15ms | -12.190
| ChannelStore.GetSidebarCategory |  Avg| 10ms| 9ms | -1ms | -10.486
| |  P99| 44ms| 45ms | 1ms | 2.286
| ChannelStore.GetTeamChannels |  Avg| 17ms| 18ms | 1ms | 5.873
| |  P99| 25ms| 49ms | 24ms | 96.545
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.315
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 9ms | -1ms | -9.591
| |  P99| 131ms| 63ms | -68ms | -51.714
| ChannelStore.SaveMember |  Avg| 37ms| 36ms | -1ms | -2.681
| |  P99| 239ms| 232ms | -7ms | -2.925
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 35ms | -3ms | -7.940
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 28ms | -4ms | -12.669
| ChannelStore.UpdateSidebarCategories |  Avg| 43ms| 86ms | 43ms | 99.596
| |  P99| 213ms| 469ms | 256ms | 120.469
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.409
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 5ms | 1ms | 24.442
| |  P99| 41ms| 46ms | 5ms | 12.165
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 0s | -3ms | -107.147
| |  P99| 5ms| 0s | -5ms | -100.192
| FileInfoStore.AttachToPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 50ms| 47ms | -3ms | -6.049
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.277
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 6ms| 5ms | -1ms | -18.047
| |  P99| 42ms| 42ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 9ms| 8ms | -1ms | -11.357
| |  P99| 68ms| 41ms | -27ms | -39.649
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.288
| GroupStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 42ms | -3ms | -6.645
| GroupStore.GetGroups |  Avg| 3ms| 2ms | -1ms | -39.883
| |  P99| 32ms| 29ms | -3ms | -9.344
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 2ms | 1ms | 69.780
| |  P99| 18ms| 57ms | 39ms | 217.270
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 66ms| 43ms | -23ms | -35.025
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 45.617
| |  P99| 38ms| 43ms | 5ms | 13.245
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 58.824
| JobStore.Save |  Avg| 4ms| 3ms | -1ms | -26.397
| |  P99| 23ms| 18ms | -5ms | -22.124
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 21ms | 3ms | 16.713
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -28.172
| |  P99| 21ms| 8ms | -13ms | -60.536
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.830
| LinkMetadataStore.Get |  Avg| 2ms| 1ms | -1ms | -59.074
| |  P99| 25ms| 20ms | -5ms | -20.025
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 23ms | 3ms | 15.190
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 26ms | -6ms | -18.544
| PluginStore.Get |  Avg| 2ms| 1ms | -1ms | -57.013
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 4ms| 2ms | -2ms | -56.567
| |  P99| 80ms| 40ms | -40ms | -49.689
| PluginStore.SetWithOptions |  Avg| 7ms| 6ms | -1ms | -14.345
| |  P99| 69ms| 50ms | -19ms | -27.406
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 45.738
| |  P99| 44ms| 45ms | 1ms | 2.277
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 32ms | -4ms | -11.222
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 2ms | 1ms | 69.071
| |  P99| 9ms| 21ms | 12ms | 140.351
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 140.351
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 57ms| 43ms | -14ms | -24.669
| PostPriorityStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -39.343
| |  P99| 39ms| 36ms | -3ms | -7.790
| PostStore.AnalyticsPostCount |  Avg| 442ms| 223ms | -219ms | -49.537
| |  P99| 498ms| 495ms | -3ms | -0.603
| PostStore.Delete |  Avg| 12ms| 15ms | 3ms | 24.257
| |  P99| 46ms| 95ms | 49ms | 107.484
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 50ms| 47ms | -3ms | -5.998
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.720
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 35ms | -6ms | -14.615
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 25ms | -5ms | -16.792
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.773
| PostStore.GetPostReminders |  Avg| 5ms| 9ms | 4ms | 77.638
| |  P99| 22ms| 92ms | 70ms | 311.804
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.399
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -37.596
| |  P99| 18ms| 5ms | -13ms | -71.826
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 37ms | -2ms | -5.145
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.019
| PostStore.GetPostsSince |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 82ms| 82ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 1ms | -1ms | -56.569
| |  P99| 24ms| 18ms | -6ms | -25.088
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 92ms| 89ms | -3ms | -3.254
| PostStore.SearchPostsForUser |  Avg| 174ms| 179ms | 5ms | 2.881
| |  P99| 2.332s| 2.34s | 8ms | 0.343
| PostStore.SetPostReminder |  Avg| 5ms| 7ms | 2ms | 39.003
| |  P99| 10ms| 24ms | 14ms | 141.209
| PostStore.Update |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 165ms| 97ms | -68ms | -41.337
| PreferenceStore.DeleteCategoryAndName |  Avg| 6ms| 4ms | -2ms | -33.111
| |  P99| 48ms| 24ms | -24ms | -50.258
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 36ms| 34ms | -2ms | -5.591
| PreferenceStore.GetAll |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.097
| PreferenceStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 126ms| 95ms | -31ms | -24.557
| ProductNoticesStore.ClearOldNotices |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 48ms| 46ms | -2ms | -4.162
| |  P99| 404ms| 364ms | -40ms | -9.905
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 26ms| 23ms | -3ms | -11.447
| ReactionStore.Save |  Avg| 11ms| 10ms | -1ms | -9.400
| |  P99| 83ms| 81ms | -2ms | -2.420
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 5ms | 1ms | 23.370
| |  P99| 22ms| 24ms | 2ms | 9.178
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 7ms | -1ms | -12.770
| |  P99| 87ms| 85ms | -2ms | -2.293
| SessionStore.GetSessionsExpired |  Avg| 3ms| 1ms | -2ms | -78.050
| |  P99| 10ms| 5ms | -5ms | -51.813
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.093
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -78.285
| SessionStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 69ms | -10ms | -12.652
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 24ms | -2ms | -7.743
| StatusStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 37ms | -6ms | -14.015
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.322
| StatusStore.SaveOrUpdate |  Avg| 64ms| 4ms | -60ms | -93.839
| |  P99| 809ms| 37ms | -772ms | -95.483
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 4ms| 2ms | -2ms | -52.656
| |  P99| 46ms| 9ms | -37ms | -80.874
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 40ms | -3ms | -7.047
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 8ms | 7ms | 888.725
| |  P99| 5ms| 48ms | 43ms | 868.687
| TeamStore.Get |  Avg| 2ms| 1ms | -1ms | -65.889
| |  P99| 24ms| 19ms | -5ms | -20.968
| TeamStore.GetAllPage |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.534
| TeamStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 41ms | 17ms | 71.881
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.307
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.533
| TeamStore.GetTeamsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.526
| TeamStore.SaveMember |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 189ms| 170ms | -19ms | -10.072
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.921
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 4ms | -1ms | -21.863
| |  P99| 49ms| 48ms | -1ms | -2.028
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 37ms | -3ms | -7.579
| ThreadStore.GetTotalThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.351
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.794
| ThreadStore.GetTotalUnreadThreads |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 41ms | -1ms | -2.381
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 46ms | -2ms | -4.210
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 41.991
| |  P99| 9ms| 20ms | 11ms | 125.715
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 3ms | -1ms | -28.100
| |  P99| 22ms| 21ms | -1ms | -4.469
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.842
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -47.045
| |  P99| 22ms| 5ms | -17ms | -77.274
| UserStore.AnalyticsActiveCount |  Avg| 18ms| 20ms | 2ms | 11.318
| |  P99| 25ms| 49ms | 24ms | 96.304
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 51ms| 50ms | -1ms | -1.979
| |  P99| 296ms| 314ms | 18ms | 6.079
| UserStore.Count |  Avg| 13ms| 14ms | 1ms | 7.474
| |  P99| 25ms| 38ms | 13ms | 52.338
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.898
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 31ms | -4ms | -11.461
| UserStore.GetAllProfilesInChannel |  Avg| 293ms| 291ms | -2ms | -0.682
| |  P99| 983ms| 975ms | -8ms | -0.814
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 34ms | 13ms | 61.787
| UserStore.GetForLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.225
| UserStore.GetMany |  Avg| 2ms| 1ms | -1ms | -56.988
| |  P99| 9ms| 5ms | -4ms | -42.781
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 34ms| 31ms | -3ms | -8.896
| UserStore.GetProfilesInChannel |  Avg| 166ms| 169ms | 3ms | 1.810
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 2ms | -1ms | -33.719
| |  P99| 36ms| 30ms | -6ms | -16.473
| UserStore.IsEmpty |  Avg| 2ms| 1ms | -1ms | -60.986
| |  P99| 24ms| 22ms | -2ms | -8.416
| UserStore.Save |  Avg| 77ms| 76ms | -1ms | -1.306
| |  P99| 239ms| 236ms | -3ms | -1.253
| UserStore.Search |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 9ms| 8ms | -1ms | -11.323
| |  P99| 68ms| 48ms | -20ms | -29.630
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 44ms | -2ms | -4.322
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 39ms| 37ms | -2ms | -5.184
| UserTermsOfServiceStore.GetByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 7ms| 6ms | -1ms | -15.335
| |  P99| 49ms| 48ms | -1ms | -2.024
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 273ms| 267ms | -6ms | -2.196
| | P99| 700ms| 803ms | 103ms | 14.715
| addTeamMember | Avg| 968ms| 947ms | -21ms | -2.169
| | P99| 4.212s| 3.59s | -622ms | -14.767
| autocompleteChannelsForTeamForSearch | Avg| 30ms| 56ms | 26ms | 87.320
| | P99| 210ms| 248ms | 38ms | 18.106
| autocompleteUsers | Avg| 40ms| 41ms | 1ms | 2.504
| | P99| 239ms| 251ms | 12ms | 5.025
| createCategoryForTeamForUser | Avg| 22ms| 28ms | 6ms | 27.673
| | P99| 25ms| 50ms | 25ms | 100.604
| createChannel | Avg| 17ms| 18ms | 1ms | 5.834
| | P99| 25ms| 49ms | 24ms | 96.545
| createDirectChannel | Avg| 269ms| 261ms | -8ms | -2.979
| | P99| 663ms| 496ms | -167ms | -25.207
| createGroupChannel | Avg| 431ms| 401ms | -30ms | -6.968
| | P99| 2.105s| 972ms | -1.133s | -53.824
| createPost | Avg| 505ms| 479ms | -26ms | -5.148
| | P99| 2.514s| 2.475s | -39ms | -1.551
| createUser | Avg| 114ms| 113ms | -1ms | -0.874
| | P99| 461ms| 436ms | -25ms | -5.423
| deleteDraft | Avg| 1ms| 3ms | 2ms | 209.760
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 18ms| 36ms | 18ms | 97.346
| | P99| 91ms| 242ms | 151ms | 165.613
| followThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 92ms | 67ms | 269.944
| getAllTeams | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| getAnalytics | Avg| 31ms| 24ms | -7ms | -22.573
| | P99| 50ms| 49ms | -1ms | -2.005
| getCategoriesForTeamForUser | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 133ms| 118ms | -15ms | -11.258
| getChannel | Avg| 5ms| 4ms | -1ms | -20.689
| | P99| 83ms| 32ms | -51ms | -61.817
| getChannelMember | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 127ms| 100ms | -27ms | -21.218
| getChannelMembers | Avg| 4ms| 6ms | 2ms | 44.656
| | P99| 5ms| 10ms | 5ms | 101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 43ms| 42ms | -1ms | -2.301
| getChannelMembersForUser | Avg| 11ms| 13ms | 2ms | 18.440
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelStats | Avg| 5ms| 4ms | -1ms | -21.808
| | P99| 78ms| 73ms | -5ms | -6.423
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 19ms | 2ms | 11.528
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 46ms| 44ms | -2ms | -4.392
| getChannelsForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 127ms| 145ms | 18ms | 14.174
| getClientConfig | Avg| 10ms| 9ms | -1ms | -10.202
| | P99| 110ms| 95ms | -15ms | -13.610
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 47ms| 46ms | -1ms | -2.143
| | P99| 226ms| 221ms | -5ms | -2.212
| getFileThumbnail | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 158ms| 139ms | -19ms | -12.011
| getFilteredUsersStats | Avg| 20ms| 15ms | -5ms | -25.490
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getLicenseSelfServeStatus | Avg| 18ms| 70ms | 52ms | 285.937
| | P99| 99ms| 245ms | 146ms | 148.220
| getPostThread | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 97ms| 94ms | -3ms | -3.093
| getPostsForChannel | Avg| 27ms| 26ms | -1ms | -3.645
| | P99| 246ms| 234ms | -12ms | -4.885
| getPostsForChannelAroundLastUnread | Avg| 28ms| 32ms | 4ms | 14.406
| | P99| 283ms| 475ms | 192ms | 67.810
| getPreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 50ms| 48ms | -2ms | -4.037
| getProfileImage | Avg| 103ms| 98ms | -5ms | -4.842
| | P99| 484ms| 483ms | -1ms | -0.207
| getPublicChannelsForTeam | Avg| 22ms| 20ms | -2ms | -8.996
| | P99| 90ms| 50ms | -40ms | -44.317
| getRolesByNames | Avg| 2ms| 1ms | -1ms | -44.774
| | P99| 10ms| 5ms | -5ms | -51.281
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 42ms | 3ms | 7.626
| getTeamMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 63ms| 57ms | -6ms | -9.480
| getTeamsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 45ms| 42ms | -3ms | -6.720
| getTeamsUnreadForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 80ms| 75ms | -5ms | -6.256
| getThreadsForUser | Avg| 5ms| 4ms | -1ms | -21.950
| | P99| 46ms| 45ms | -1ms | -2.165
| getUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 82ms| 82ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 0s | -1ms | -198.351
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 136ms| 162ms | 26ms | 19.149
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.387
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 35ms| 32ms | -3ms | -8.680
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 79ms| 78ms | -1ms | -1.270
| | P99| 496ms| 483ms | -13ms | -2.618
| logout | Avg| 49ms| 54ms | 5ms | 10.152
| | P99| 217ms| 99ms | -118ms | -54.339
| patchPost | Avg| 125ms| 271ms | 146ms | 117.032
| | P99| 484ms| 905ms | 421ms | 87.031
| removeUserCustomStatus | Avg| 197ms| 212ms | 15ms | 7.595
| | P99| 685ms| 492ms | -193ms | -28.174
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 186ms| 185ms | -1ms | -0.538
| searchAllChannels | Avg| 46ms| 46ms | 0s | 0.000
| | P99| 100ms| 129ms | 29ms | 29.060
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 38ms| 35ms | -3ms | -7.808
| searchPostsInTeam | Avg| 181ms| 189ms | 8ms | 4.418
| | P99| 2.348s| 2.355s | 7ms | 0.298
| searchUsers | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 16ms | 1ms | 6.684
| | P99| 47ms| 25ms | -22ms | -47.295
| unfollowThreadByUser | Avg| 11ms| 10ms | -1ms | -9.489
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 64ms| 107ms | 43ms | 66.927
| | P99| 213ms| 488ms | 275ms | 129.410
| updatePreferences | Avg| 9ms| 8ms | -1ms | -11.747
| | P99| 77ms| 76ms | -1ms | -1.304
| updateReadStateAllThreadsByUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 36ms| 35ms | -1ms | -2.808
| | P99| 212ms| 204ms | -8ms | -3.782
| updateUserCustomStatus | Avg| 204ms| 213ms | 9ms | 4.402
| | P99| 680ms| 493ms | -187ms | -27.501
| uploadFileStream | Avg| 469ms| 457ms | -12ms | -2.560
| | P99| 1.94s| 1.655s | -285ms | -14.691
| upsertDraft | Avg| 4ms| 0s | -4ms | -102.546
| | P99| 5ms| 0s | -5ms | -100.192
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 104ms| 96ms | -8ms | -7.693
