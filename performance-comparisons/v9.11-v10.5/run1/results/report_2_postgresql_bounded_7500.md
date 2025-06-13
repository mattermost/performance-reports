### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMembersForUser | avg | 3ms | 5ms | 2ms | 59.53
| ChannelStore.UpdateSidebarCategories | avg | 25ms | 29ms | 4ms | 15.87
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 14ms | 16ms | 2ms | 14.73
| UserStore.GetAllProfilesInChannel | avg | 156ms | 170ms | 14ms | 8.95
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 26ms | 21ms | 411.76
| UserStore.GetMany | p99 | 5ms | 21ms | 16ms | 323.23
| ChannelStore.Save | p99 | 24ms | 58ms | 34ms | 143.42
| JobStore.GetCountByStatusAndType | p99 | 8ms | 18ms | 10ms | 132.45
| FileInfoStore.GetByIds | p99 | 5ms | 11ms | 6ms | 120.25
| ReactionStore.GetForPost | p99 | 10ms | 20ms | 10ms | 104.29
| UserAccessTokenStore.GetByToken | p99 | 5ms | 10ms | 5ms | 101.01
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 18ms | 9ms | 96.78
| ChannelStore.UpdateSidebarCategories | p99 | 49ms | 93ms | 44ms | 88.95
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.80
| PostStore.GetPostIdAfterTime | p99 | 9ms | 15ms | 6ms | 67.69
| ChannelStore.CreateDirectChannel | p99 | 46ms | 77ms | 31ms | 66.72
| ThreadStore.GetMembershipForUser | p99 | 9ms | 15ms | 6ms | 66.49
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 109ms | 178ms | 69ms | 63.30
| ChannelStore.GetFileCount | p99 | 9ms | 15ms | 6ms | 63.30
| PreferenceStore.Get | p99 | 10ms | 15ms | 5ms | 50.07
| PostStore.SearchPostsForUser | p99 | 425ms | 598ms | 173ms | 40.71
| ChannelStore.CreateInitialSidebarCategories | p99 | 49ms | 68ms | 19ms | 38.40
| StatusStore.Get | p99 | 14ms | 19ms | 5ms | 35.55
| SystemStore.GetByName | p99 | 12ms | 16ms | 4ms | 33.76
| UserStore.GetProfilesByUsernames | p99 | 9ms | 12ms | 3ms | 31.80
| ChannelStore.GetMemberForPost | p99 | 13ms | 17ms | 4ms | 31.28
| PostPersistentNotificationStore.GetSingle | p99 | 6ms | 8ms | 2ms | 31.10
| PostStore.GetPostIdBeforeTime | p99 | 6ms | 8ms | 2ms | 30.78
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 13ms | 17ms | 4ms | 30.40
| UserStore.GetProfileByIds | p99 | 13ms | 17ms | 4ms | 30.35
| ThreadStore.MaintainMembership | p99 | 14ms | 18ms | 4ms | 29.46
| TeamStore.Get | p99 | 7ms | 9ms | 2ms | 29.26
| StatusStore.GetByIds | p99 | 7ms | 9ms | 2ms | 26.71
| RoleStore.ChannelHigherScopedPermissions | p99 | 19ms | 24ms | 5ms | 25.65
| ChannelStore.GetMemberLastViewedAt | p99 | 16ms | 20ms | 4ms | 25.06
| PluginStore.Delete | p99 | 8ms | 10ms | 2ms | 23.68
| ThreadStore.GetTotalUnreadMentions | p99 | 17ms | 21ms | 4ms | 23.43
| GroupStore.GetGroups | p99 | 13ms | 16ms | 3ms | 22.53
| ChannelStore.GetChannels | p99 | 14ms | 17ms | 3ms | 21.95
| UserStore.GetForLogin | p99 | 18ms | 22ms | 4ms | 21.65
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 14ms | 17ms | 3ms | 20.83
| PostStore.Save | p99 | 29ms | 35ms | 6ms | 20.49
| ThreadStore.GetThreadFollowers | p99 | 10ms | 12ms | 2ms | 20.30
| ChannelStore.GetMembersForUser | p99 | 15ms | 18ms | 3ms | 20.07
| ChannelStore.Get | p99 | 16ms | 19ms | 3ms | 19.32
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 17ms | 20ms | 3ms | 17.85
| ThreadStore.GetTotalUnreadThreads | p99 | 17ms | 20ms | 3ms | 17.85
| ThreadStore.GetTotalThreads | p99 | 17ms | 20ms | 3ms | 17.68
| ChannelStore.GetChannelsByUser | p99 | 17ms | 20ms | 3ms | 17.43
| UserStore.GetAllProfiles | p99 | 17ms | 20ms | 3ms | 17.34
| DraftStore.GetDraftsForUser | p99 | 12ms | 14ms | 2ms | 16.76
| ChannelStore.IncrementMentionCount | p99 | 13ms | 15ms | 2ms | 15.53
| PostStore.GetPostsBefore | p99 | 15ms | 17ms | 2ms | 13.16
| SessionStore.Get | p99 | 33ms | 37ms | 4ms | 12.30
| PostStore.GetEtag | p99 | 17ms | 19ms | 2ms | 12.03
| TeamStore.SaveMember | p99 | 62ms | 69ms | 7ms | 11.20
| UserTermsOfServiceStore.GetByUser | p99 | 18ms | 20ms | 2ms | 10.85
| PostStore.GetPosts | p99 | 19ms | 21ms | 2ms | 10.70
| TeamStore.GetTeamsByUserId | p99 | 19ms | 21ms | 2ms | 10.63
| TeamStore.GetTeamsForUser | p99 | 19ms | 21ms | 2ms | 10.62
| UserStore.UpdateUpdateAt | p99 | 19ms | 21ms | 2ms | 10.55
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 48ms | 53ms | 5ms | 10.39
| TeamStore.GetAllPage | p99 | 19ms | 21ms | 2ms | 10.29
| ChannelStore.SearchGroupChannels | p99 | 22ms | 24ms | 2ms | 9.11
| ChannelStore.GetGuestCount | p99 | 22ms | 24ms | 2ms | 9.11
| ChannelStore.SaveMember | p99 | 88ms | 94ms | 6ms | 6.82
| UserStore.GetAllProfilesInChannel | p99 | 477ms | 487ms | 10ms | 2.09
| ProductNoticesStore.View | p99 | 97ms | 99ms | 2ms | 2.06
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SharedChannelStore.HasChannel | avg | 2ms | 0s | -2ms | -112.25
| RoleStore.GetByNames | avg | 5ms | 0s | -5ms | -107.82
| ChannelStore.IsReadOnlyChannel | avg | 2ms | 0s | -2ms | -105.88
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -104.86
| ChannelStore.CreateSidebarCategory | avg | 14ms | 0s | -14ms | -100.13
| ChannelBookmarkStore.Save | avg | 8ms | 0s | -8ms | -97.83
| ChannelBookmarkStore.UpdateSortOrder | avg | 3ms | 0s | -3ms | -97.74
| ScheduledPostStore.GetScheduledPostsForUser | avg | 2ms | 0s | -2ms | -90.34
| ChannelBookmarkStore.Delete | avg | 3ms | 0s | -3ms | -87.95
| ScheduledPostStore.GetPendingScheduledPosts | avg | 2ms | 0s | -2ms | -87.26
| ScheduledPostStore.CreateScheduledPost | avg | 2ms | 0s | -2ms | -80.05
| StatusStore.SaveOrUpdate | avg | 10ms | 3ms | -7ms | -71.04
| ChannelStore.AutocompleteInTeamForSearch | avg | 26ms | 14ms | -12ms | -46.45
| PostStore.AnalyticsPostCount | avg | 464ms | 426ms | -38ms | -8.19
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SharedChannelStore.HasChannel | p99 | 8ms | 0s | -8ms | -104.81
| ChannelStore.IsReadOnlyChannel | p99 | 9ms | 0s | -9ms | -102.16
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.UpdateSortOrder | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.GetMaxMessageSize | p99 | 5ms | 0s | -5ms | -100.95
| ChannelStore.CreateSidebarCategory | p99 | 25ms | 0s | -25ms | -100.60
| ChannelBookmarkStore.Save | p99 | 47ms | 0s | -47ms | -100.53
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 16ms | 0s | -16ms | -99.37
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 22ms | 0s | -22ms | -98.00
| StatusStore.SaveOrUpdate | p99 | 205ms | 22ms | -183ms | -89.33
| RoleStore.GetByNames | p99 | 24ms | 5ms | -19ms | -79.33
| LinkMetadataStore.Save | p99 | 23ms | 5ms | -18ms | -78.86
| PostStore.SetPostReminder | p99 | 23ms | 5ms | -18ms | -78.09
| ChannelStore.GetSidebarCategory | p99 | 76ms | 24ms | -52ms | -68.43
| FileInfoStore.SetContent | p99 | 61ms | 21ms | -40ms | -65.57
| UserStore.GetByUsername | p99 | 22ms | 8ms | -14ms | -63.22
| ChannelStore.GetTeamChannels | p99 | 24ms | 10ms | -14ms | -57.38
| TeamStore.GetMember | p99 | 13ms | 6ms | -7ms | -54.10
| BotStore.Get | p99 | 10ms | 5ms | -5ms | -52.22
| SessionStore.GetSessionsExpired | p99 | 10ms | 5ms | -5ms | -51.81
| ChannelStore.AutocompleteInTeamForSearch | p99 | 94ms | 48ms | -46ms | -49.00
| JobStore.UpdateOptimistically | p99 | 9ms | 5ms | -4ms | -45.33
| JobStore.UpdateStatus | p99 | 9ms | 5ms | -4ms | -43.40
| FileInfoStore.AttachToPost | p99 | 19ms | 11ms | -8ms | -41.41
| PostPriorityStore.GetForPost | p99 | 17ms | 11ms | -6ms | -35.09
| UserStore.GetUnreadCount | p99 | 16ms | 12ms | -4ms | -25.38
| PostAcknowledgementStore.GetForPost | p99 | 21ms | 16ms | -5ms | -24.21
| ChannelStore.GetPublicChannelsForTeam | p99 | 50ms | 40ms | -10ms | -20.16
| WebhookStore.GetOutgoingByTeam | p99 | 34ms | 30ms | -4ms | -11.75
| ChannelStore.GetByName | p99 | 39ms | 35ms | -4ms | -10.33
| ClusterDiscoveryStore.SetLastPingAt | p99 | 20ms | 18ms | -2ms | -10.17
| JobStore.GetAllByStatus | p99 | 23ms | 21ms | -2ms | -8.61
| UserStore.Save | p99 | 210ms | 204ms | -6ms | -2.86
| UserStore.AutocompleteUsersInChannel | p99 | 170ms | 167ms | -3ms | -1.77
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 22ms | 54ms | 32ms | 147.78
| logout | avg | 22ms | 38ms | 16ms | 71.39
| getChannel | avg | 4ms | 7ms | 3ms | 67.48
| login | avg | 57ms | 80ms | 23ms | 40.19
| createPost | avg | 177ms | 247ms | 70ms | 39.56
| createGroupChannel | avg | 269ms | 354ms | 85ms | 31.55
| removeUserCustomStatus | avg | 107ms | 140ms | 33ms | 30.84
| addChannelMember | avg | 168ms | 203ms | 35ms | 20.77
| createDirectChannel | avg | 184ms | 213ms | 29ms | 15.80
| createUser | avg | 121ms | 133ms | 12ms | 9.89
| getTeamStats | avg | 35ms | 38ms | 3ms | 8.54
| addTeamMember | avg | 586ms | 629ms | 43ms | 7.34
| autocompleteUsers | avg | 31ms | 33ms | 2ms | 6.37
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 50ms | 1.667s | 1.617s | 3243.63
| login | p99 | 243ms | 466ms | 223ms | 91.66
| getChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| getChannel | p99 | 15ms | 24ms | 9ms | 59.60
| updatePreferences | p99 | 14ms | 21ms | 7ms | 49.25
| searchPostsInTeam | p99 | 425ms | 598ms | 173ms | 40.71
| updateUserCustomStatus | p99 | 5ms | 7ms | 2ms | 40.40
| saveReaction | p99 | 25ms | 35ms | 10ms | 40.17
| getPostsForChannelAroundLastUnread | p99 | 62ms | 85ms | 23ms | 37.35
| getClientConfig | p99 | 29ms | 39ms | 10ms | 34.17
| getUsersByNames | p99 | 10ms | 13ms | 3ms | 31.25
| createUser | p99 | 345ms | 448ms | 103ms | 29.84
| getPostThread | p99 | 28ms | 36ms | 8ms | 28.86
| getTeamsUnreadForUser | p99 | 25ms | 32ms | 7ms | 27.70
| getDrafts | p99 | 12ms | 15ms | 3ms | 25.14
| getChannelsForUser | p99 | 17ms | 21ms | 4ms | 22.93
| getCategoriesForTeamForUser | p99 | 49ms | 60ms | 11ms | 22.52
| getChannelStats | p99 | 27ms | 33ms | 6ms | 21.92
| getChannelsForTeamForUser | p99 | 14ms | 17ms | 3ms | 21.50
| listChannelBookmarksForChannel | p99 | 9ms | 11ms | 2ms | 21.45
| createGroupChannel | p99 | 496ms | 600ms | 104ms | 20.95
| getChannelMembersForTeamForUser | p99 | 15ms | 18ms | 3ms | 19.98
| createPost | p99 | 808ms | 945ms | 137ms | 16.97
| getTeamsForUser | p99 | 19ms | 22ms | 3ms | 15.84
| addTeamMember | p99 | 1.989s | 2.284s | 295ms | 14.83
| getUsers | p99 | 22ms | 25ms | 3ms | 13.38
| getChannelMember | p99 | 37ms | 41ms | 4ms | 10.72
| getThreadsForUser | p99 | 20ms | 22ms | 2ms | 9.86
| getTeamMembersForUser | p99 | 21ms | 23ms | 2ms | 9.64
| searchGroupChannels | p99 | 22ms | 24ms | 2ms | 9.11
| getPreferences | p99 | 22ms | 24ms | 2ms | 8.94
| getUser | p99 | 23ms | 25ms | 2ms | 8.64
| updateReadStateThreadByUser | p99 | 91ms | 96ms | 5ms | 5.50
| addChannelMember | p99 | 463ms | 482ms | 19ms | 4.11
| removeUserCustomStatus | p99 | 348ms | 362ms | 14ms | 4.03
| getPostsForChannel | p99 | 173ms | 179ms | 6ms | 3.46
| createDirectChannel | p99 | 483ms | 493ms | 10ms | 2.07
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamScheduledPosts | avg | 5ms | 0s | -5ms | -108.69
| createSchedulePost | avg | 3ms | 0s | -3ms | -104.37
| updateChannelBookmark | avg | 14ms | 0s | -14ms | -102.51
| createCategoryForTeamForUser | avg | 16ms | 0s | -16ms | -100.92
| createChannelBookmark | avg | 15ms | 0s | -15ms | -97.01
| updateChannelBookmarkSortOrder | avg | 3ms | 0s | -3ms | -93.85
| autocompleteChannelsForTeamForSearch | avg | 26ms | 14ms | -12ms | -46.33
| viewChannel | avg | 10ms | 8ms | -2ms | -19.95
| uploadFileStream | avg | 379ms | 371ms | -8ms | -2.11
| createChannel | avg | 204ms | 201ms | -3ms | -1.47
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamScheduledPosts | p99 | 25ms | 0s | -25ms | -101.79
| updateChannelBookmarkSortOrder | p99 | 5ms | 0s | -5ms | -101.01
| createSchedulePost | p99 | 5ms | 0s | -5ms | -100.95
| createCategoryForTeamForUser | p99 | 25ms | 0s | -25ms | -100.60
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| createChannelBookmark | p99 | 48ms | 0s | -48ms | -100.52
| updateCategoriesForTeamForUser | p99 | 214ms | 99ms | -115ms | -53.69
| autocompleteChannelsForTeamForSearch | p99 | 94ms | 48ms | -46ms | -49.00
| getPublicChannelsForTeam | p99 | 50ms | 40ms | -10ms | -20.16
| viewChannel | p99 | 39ms | 37ms | -2ms | -5.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.618
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.219
| ChannelBookmarkStore.Delete |  Avg| 3ms| 0s | -3ms | -87.947
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -104.857
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.556
| ChannelBookmarkStore.Save |  Avg| 8ms| 0s | -8ms | -97.831
| |  P99| 47ms| 0s | -47ms | -100.532
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 3ms| 0s | -3ms | -97.735
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.403
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 99ms| 98ms | -1ms | -1.014
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 26ms| 14ms | -12ms | -46.447
| |  P99| 94ms| 48ms | -46ms | -49.001
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 17ms | 1ms | 6.395
| |  P99| 46ms| 77ms | 31ms | 66.722
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 14ms | 1ms | 7.411
| |  P99| 49ms| 68ms | 19ms | 38.396
| ChannelStore.CreateSidebarCategory |  Avg| 14ms| 0s | -14ms | -100.133
| |  P99| 25ms| 0s | -25ms | -100.604
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 19ms | 3ms | 19.318
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 5ms | 2ms | 59.533
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 16ms | 2ms | 14.728
| |  P99| 109ms| 178ms | 69ms | 63.299
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 35ms | -4ms | -10.331
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.948
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 3ms | 1ms | 41.165
| |  P99| 17ms| 20ms | 3ms | 17.431
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.092
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 15ms | 6ms | 63.298
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 24ms | 2ms | 9.112
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.278
| ChannelStore.GetMemberCount |  Avg| 14ms| 15ms | 1ms | 6.943
| |  P99| 47ms| 48ms | 1ms | 2.147
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 31.276
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 20ms | 4ms | 25.059
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 20.069
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.748
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 96.775
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 50ms| 40ms | -10ms | -20.164
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 53ms | 5ms | 10.390
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 7ms | -1ms | -12.243
| |  P99| 76ms| 24ms | -52ms | -68.428
| ChannelStore.GetTeamChannels |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 24ms| 10ms | -14ms | -57.375
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.532
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 0s | -2ms | -105.876
| |  P99| 9ms| 0s | -9ms | -102.161
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 58ms | 34ms | 143.422
| ChannelStore.SaveMember |  Avg| 24ms| 25ms | 1ms | 4.120
| |  P99| 88ms| 94ms | 6ms | 6.825
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 30.851
| |  P99| 22ms| 24ms | 2ms | 9.112
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.448
| ChannelStore.UpdateSidebarCategories |  Avg| 25ms| 29ms | 4ms | 15.872
| |  P99| 49ms| 93ms | 44ms | 88.948
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.173
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 3ms | 1ms | 40.875
| |  P99| 12ms| 14ms | 2ms | 16.763
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 8.771
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.930
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 11ms | -8ms | -41.408
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 11ms | 6ms | 120.250
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.823
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 61ms| 21ms | -40ms | -65.573
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 20.826
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 22.534
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.609
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 132.450
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 26ms | 21ms | 411.765
| JobStore.Save |  Avg| 2ms| 3ms | 1ms | 49.633
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.326
| JobStore.UpdateStatus |  Avg| 3ms| 2ms | -1ms | -37.530
| |  P99| 9ms| 5ms | -4ms | -43.400
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 13.028
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -26.328
| |  P99| 23ms| 5ms | -18ms | -78.864
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 23.677
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.860
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.212
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.308
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.105
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 11ms | -6ms | -35.085
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.085
| PostStore.AnalyticsPostCount |  Avg| 464ms| 426ms | -38ms | -8.185
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.271
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 19ms | 2ms | 12.028
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 15ms | 6ms | 67.686
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 30.776
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 43.180
| |  P99| 5ms| 9ms | 4ms | 80.796
| PostStore.GetPostReminders |  Avg| 3ms| 4ms | 1ms | 35.759
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 3ms| 4ms | 1ms | 29.840
| |  P99| 19ms| 21ms | 2ms | 10.702
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -36.972
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.159
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.210
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.820
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 29ms| 35ms | 6ms | 20.493
| PostStore.SearchPostsForUser |  Avg| 24ms| 25ms | 1ms | 4.182
| |  P99| 425ms| 598ms | 173ms | 40.712
| PostStore.SetPostReminder |  Avg| 5ms| 4ms | -1ms | -19.642
| |  P99| 23ms| 5ms | -18ms | -78.094
| PostStore.Update |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.076
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 50.073
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.526
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.441
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 20ms| 19ms | -1ms | -5.103
| |  P99| 97ms| 99ms | 2ms | 2.065
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 20ms | 10ms | 104.286
| RoleStore.ChannelHigherScopedPermissions |  Avg| 4ms| 5ms | 1ms | 24.037
| |  P99| 19ms| 24ms | 5ms | 25.647
| RoleStore.GetByNames |  Avg| 5ms| 0s | -5ms | -107.822
| |  P99| 24ms| 5ms | -19ms | -79.331
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 0s | -2ms | -80.050
| |  P99| 5ms| 0s | -5ms | -101.010
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -100.951
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 0s | -2ms | -87.258
| |  P99| 22ms| 0s | -22ms | -97.996
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 0s | -2ms | -90.342
| |  P99| 16ms| 0s | -16ms | -99.366
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 0s | -1ms | -127.503
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 37ms | 4ms | 12.303
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 3ms| 2ms | -1ms | -35.327
| |  P99| 10ms| 5ms | -5ms | -51.813
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.190
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.121
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 0s | -2ms | -112.255
| |  P99| 8ms| 0s | -8ms | -104.812
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 19ms | 5ms | 35.552
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 26.713
| StatusStore.SaveOrUpdate |  Avg| 10ms| 3ms | -7ms | -71.039
| |  P99| 205ms| 22ms | -183ms | -89.330
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 16ms | 4ms | 33.760
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 9ms | 2ms | 29.257
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 36ms | 1ms | 2.860
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.294
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 3ms | 1ms | 40.028
| |  P99| 20ms| 20ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 1ms | -1ms | -58.450
| |  P99| 13ms| 6ms | -7ms | -54.105
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.625
| TeamStore.GetTeamsForUser |  Avg| 2ms| 3ms | 1ms | 42.276
| |  P99| 19ms| 21ms | 2ms | 10.617
| TeamStore.GetTotalMemberCount |  Avg| 35ms| 36ms | 1ms | 2.872
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 20ms| 21ms | 1ms | 4.901
| |  P99| 62ms| 69ms | 7ms | 11.200
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 15ms | 6ms | 66.494
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.841
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.299
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.194
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.685
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 3ms | 1ms | 41.274
| |  P99| 17ms| 21ms | 4ms | 23.431
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 3ms | 1ms | 42.782
| |  P99| 17ms| 20ms | 3ms | 17.850
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 3ms | 1ms | 40.996
| |  P99| 17ms| 20ms | 3ms | 17.851
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 18ms | 4ms | 29.462
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 3ms | 1ms | 55.788
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 37ms | 1ms | 2.759
| |  P99| 170ms| 167ms | -3ms | -1.766
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.220
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.336
| UserStore.GetAllProfilesInChannel |  Avg| 156ms| 170ms | 14ms | 8.947
| |  P99| 477ms| 487ms | 10ms | 2.095
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 8ms | -14ms | -63.225
| UserStore.GetForLogin |  Avg| 2ms| 3ms | 1ms | 40.544
| |  P99| 18ms| 22ms | 4ms | 21.648
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 17ms | 4ms | 30.347
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 31.799
| UserStore.GetProfilesInChannel |  Avg| 10ms| 11ms | 1ms | 9.757
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -25.385
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.Save |  Avg| 74ms| 73ms | -1ms | -1.357
| |  P99| 210ms| 204ms | -6ms | -2.858
| UserStore.Search |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 68ms| 67ms | -1ms | -1.477
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.403
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.287
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.177
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.549
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.852
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 30ms | -4ms | -11.754
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 168ms| 203ms | 35ms | 20.774
| | P99| 463ms| 482ms | 19ms | 4.105
| addTeamMember | Avg| 586ms| 629ms | 43ms | 7.336
| | P99| 1.989s| 2.284s | 295ms | 14.834
| autocompleteChannelsForTeamForSearch | Avg| 26ms| 14ms | -12ms | -46.334
| | P99| 94ms| 48ms | -46ms | -49.001
| autocompleteUsers | Avg| 31ms| 33ms | 2ms | 6.373
| | P99| 151ms| 152ms | 1ms | 0.662
| createCategoryForTeamForUser | Avg| 16ms| 0s | -16ms | -100.916
| | P99| 25ms| 0s | -25ms | -100.604
| createChannel | Avg| 204ms| 201ms | -3ms | -1.473
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 15ms| 0s | -15ms | -97.008
| | P99| 48ms| 0s | -48ms | -100.522
| createDirectChannel | Avg| 184ms| 213ms | 29ms | 15.798
| | P99| 483ms| 493ms | 10ms | 2.068
| createGroupChannel | Avg| 269ms| 354ms | 85ms | 31.550
| | P99| 496ms| 600ms | 104ms | 20.950
| createPost | Avg| 177ms| 247ms | 70ms | 39.562
| | P99| 808ms| 945ms | 137ms | 16.966
| createSchedulePost | Avg| 3ms| 0s | -3ms | -104.371
| | P99| 5ms| 0s | -5ms | -100.951
| createUser | Avg| 121ms| 133ms | 12ms | 9.885
| | P99| 345ms| 448ms | 103ms | 29.845
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.716
| getCategoriesForTeamForUser | Avg| 14ms| 15ms | 1ms | 7.072
| | P99| 49ms| 60ms | 11ms | 22.517
| getChannel | Avg| 4ms| 7ms | 3ms | 67.475
| | P99| 15ms| 24ms | 9ms | 59.602
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 37ms| 41ms | 4ms | 10.720
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 18ms | 3ms | 19.978
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.710
| getChannelStats | Avg| 2ms| 3ms | 1ms | 40.095
| | P99| 27ms| 33ms | 6ms | 21.923
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.808
| getChannelsForTeamForUser | Avg| 2ms| 3ms | 1ms | 40.662
| | P99| 14ms| 17ms | 3ms | 21.502
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 21ms | 4ms | 22.929
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 29ms| 39ms | 10ms | 34.172
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 15ms | 3ms | 25.144
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 95ms| 95ms | 0s | 0.000
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 89ms| 89ms | 0s | 0.000
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 28ms| 36ms | 8ms | 28.864
| getPostsForChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 173ms| 179ms | 6ms | 3.461
| getPostsForChannelAroundLastUnread | Avg| 14ms| 15ms | 1ms | 7.066
| | P99| 62ms| 85ms | 23ms | 37.349
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 24ms | 2ms | 8.938
| getProfileImage | Avg| 68ms| 67ms | -1ms | -1.466
| | P99| 249ms| 249ms | 0s | 0.000
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 50ms| 40ms | -10ms | -20.164
| getTeamMember | Avg| 2ms| 1ms | -1ms | -65.264
| | P99| 10ms| 9ms | -1ms | -9.686
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.641
| getTeamScheduledPosts | Avg| 5ms| 0s | -5ms | -108.692
| | P99| 25ms| 0s | -25ms | -101.789
| getTeamStats | Avg| 35ms| 38ms | 3ms | 8.545
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 3ms | 1ms | 41.841
| | P99| 19ms| 22ms | 3ms | 15.835
| getTeamsUnreadForUser | Avg| 4ms| 5ms | 1ms | 22.245
| | P99| 25ms| 32ms | 7ms | 27.701
| getThreadsForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 20ms| 22ms | 2ms | 9.861
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 25ms | 2ms | 8.637
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 4ms | 1ms | 29.595
| | P99| 22ms| 25ms | 3ms | 13.382
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 3ms | 1ms | 40.668
| | P99| 10ms| 13ms | 3ms | 31.250
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 11ms | 2ms | 21.449
| login | Avg| 57ms| 80ms | 23ms | 40.189
| | P99| 243ms| 466ms | 223ms | 91.657
| logout | Avg| 22ms| 38ms | 16ms | 71.390
| | P99| 49ms| 50ms | 1ms | 2.041
| patchPost | Avg| 22ms| 54ms | 32ms | 147.782
| | P99| 50ms| 1.667s | 1.617s | 3243.626
| removeUserCustomStatus | Avg| 107ms| 140ms | 33ms | 30.842
| | P99| 348ms| 362ms | 14ms | 4.028
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 35ms | 10ms | 40.170
| searchAllChannels | Avg| 34ms| 33ms | -1ms | -2.973
| | P99| 99ms| 98ms | -1ms | -1.014
| searchGroupChannels | Avg| 3ms| 4ms | 1ms | 30.205
| | P99| 22ms| 24ms | 2ms | 9.112
| searchPostsInTeam | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 425ms| 598ms | 173ms | 40.712
| searchUsers | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 71ms| 71ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 14ms | -1ms | -6.567
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 44ms| 45ms | 1ms | 2.288
| | P99| 214ms| 99ms | -115ms | -53.691
| updateChannelBookmark | Avg| 14ms| 0s | -14ms | -102.510
| | P99| 25ms| 0s | -25ms | -100.604
| updateChannelBookmarkSortOrder | Avg| 3ms| 0s | -3ms | -93.850
| | P99| 5ms| 0s | -5ms | -101.010
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 14ms| 21ms | 7ms | 49.250
| updateReadStateAllThreadsByUser | Avg| 4ms| 3ms | -1ms | -28.343
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 35ms| 36ms | 1ms | 2.840
| | P99| 91ms| 96ms | 5ms | 5.500
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.404
| uploadFileStream | Avg| 379ms| 371ms | -8ms | -2.109
| | P99| 983ms| 982ms | -1ms | -0.102
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.751
| viewChannel | Avg| 10ms| 8ms | -2ms | -19.946
| | P99| 39ms| 37ms | -2ms | -5.066
