### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 11ms | 72ms | 61ms | 556.39
| UserStore.GetMany | avg | 1ms | 3ms | 2ms | 266.95
| ComplianceStore.MessageExport | avg | 2ms | 6ms | 4ms | 160.16
| StatusStore.SaveOrUpdate | avg | 16ms | 25ms | 9ms | 57.44
| ChannelStore.AnalyticsTypeCount | avg | 7ms | 10ms | 3ms | 40.01
| PostStore.AnalyticsPostCount | avg | 222ms | 233ms | 11ms | 4.95
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 47ms | 2.7s | 2.653s | 5590.71
| ComplianceStore.MessageExport | p99 | 7ms | 279ms | 272ms | 3751.72
| UserStore.GetMany | p99 | 5ms | 44ms | 39ms | 787.88
| PostPriorityStore.GetForPost | p99 | 5ms | 22ms | 17ms | 341.00
| UserAccessTokenStore.GetByToken | p99 | 5ms | 18ms | 13ms | 262.54
| FileInfoStore.GetByIds | p99 | 6ms | 18ms | 12ms | 188.99
| PostAcknowledgementStore.GetForPost | p99 | 6ms | 17ms | 11ms | 169.89
| JobStore.GetNewestJobByStatusesAndType | p99 | 10ms | 24ms | 14ms | 145.08
| JobStore.UpdateStatus | p99 | 8ms | 18ms | 10ms | 130.72
| PostStore.Delete | p99 | 10ms | 23ms | 13ms | 130.61
| ChannelStore.GetMembersForUserWithPagination | p99 | 10ms | 21ms | 11ms | 110.61
| StatusStore.SaveOrUpdate | p99 | 233ms | 431ms | 198ms | 85.15
| UserStore.Count | p99 | 25ms | 43ms | 18ms | 72.45
| JobStore.GetCountByStatusAndType | p99 | 21ms | 35ms | 14ms | 68.04
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 26ms | 42ms | 16ms | 62.44
| UserStore.Update | p99 | 10ms | 16ms | 6ms | 60.86
| PluginStore.List | p99 | 5ms | 8ms | 3ms | 60.61
| ReactionStore.GetForPost | p99 | 7ms | 11ms | 4ms | 54.37
| ThreadStore.Get | p99 | 5ms | 7ms | 2ms | 40.40
| TeamStore.GetActiveMemberCount | p99 | 95ms | 99ms | 4ms | 4.21
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 0s | -3ms | -107.21
| SystemStore.Save | avg | 2ms | 0s | -2ms | -94.87
| LinkMetadataStore.Save | avg | 5ms | 2ms | -3ms | -56.16
| TeamStore.GetTotalMemberCount | avg | 52ms | 26ms | -26ms | -50.01
| PostStore.SetPostReminder | avg | 6ms | 3ms | -3ms | -49.66
| PostStore.GetPostReminders | avg | 6ms | 3ms | -3ms | -46.96
| ChannelStore.CreateDirectChannel | avg | 14ms | 11ms | -3ms | -21.90
| ChannelStore.Save | avg | 9ms | 7ms | -2ms | -21.35
| PostStore.SearchPostsForUser | avg | 190ms | 150ms | -40ms | -21.06
| PostStore.Update | avg | 11ms | 9ms | -2ms | -18.56
| UserStore.GetProfilesInChannel | avg | 16ms | 13ms | -3ms | -18.46
| ChannelStore.GetSidebarCategory | avg | 18ms | 15ms | -3ms | -17.12
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 20ms | 17ms | -3ms | -15.29
| ChannelStore.GetTeamChannels | avg | 20ms | 17ms | -3ms | -15.17
| ProductNoticesStore.View | avg | 22ms | 19ms | -3ms | -13.85
| TeamStore.SaveMember | avg | 28ms | 25ms | -3ms | -10.83
| ChannelStore.UpdateSidebarCategories | avg | 67ms | 61ms | -6ms | -8.95
| ChannelStore.SaveMember | avg | 27ms | 25ms | -2ms | -7.51
| ChannelStore.CreateInitialSidebarCategories | avg | 36ms | 34ms | -2ms | -5.52
| UserStore.AutocompleteUsersInChannel | avg | 45ms | 43ms | -2ms | -4.41
| UserStore.Save | avg | 72ms | 70ms | -2ms | -2.79
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 74ms | 72ms | -2ms | -2.71
| UserStore.GetAllProfilesInChannel | avg | 232ms | 226ms | -6ms | -2.58
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| LinkMetadataStore.Save | p99 | 47ms | 5ms | -42ms | -89.68
| ChannelStore.Save | p99 | 145ms | 30ms | -115ms | -79.31
| PostStore.GetPostReminderMetadata | p99 | 24ms | 5ms | -19ms | -78.84
| RoleStore.GetByNames | p99 | 23ms | 5ms | -18ms | -77.76
| UserStore.GetProfilesNotInChannel | p99 | 23ms | 5ms | -18ms | -76.60
| JobStore.UpdateStatusOptimistically | p99 | 21ms | 5ms | -16ms | -74.51
| RoleStore.ChannelHigherScopedPermissions | p99 | 19ms | 5ms | -14ms | -73.11
| ClusterDiscoveryStore.SetLastPingAt | p99 | 39ms | 13ms | -26ms | -66.88
| PostStore.SetPostReminder | p99 | 24ms | 9ms | -15ms | -62.24
| JobStore.Get | p99 | 35ms | 14ms | -21ms | -60.43
| ChannelStore.GetSidebarCategory | p99 | 193ms | 77ms | -116ms | -60.10
| BotStore.Get | p99 | 22ms | 9ms | -13ms | -57.91
| StatusStore.UpdateExpiredDNDStatuses | p99 | 46ms | 22ms | -24ms | -52.46
| PostStore.GetPostReminders | p99 | 46ms | 22ms | -24ms | -52.46
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 5ms | -5ms | -51.81
| UserStore.GetByUsername | p99 | 21ms | 10ms | -11ms | -51.74
| ChannelStore.GetChannelsByUser | p99 | 16ms | 8ms | -8ms | -51.45
| UserStore.GetProfilesInChannel | p99 | 49ms | 25ms | -24ms | -49.36
| ChannelStore.GetTeamChannels | p99 | 95ms | 49ms | -46ms | -48.42
| TeamStore.GetTotalMemberCount | p99 | 95ms | 50ms | -45ms | -47.37
| JobStore.UpdateOptimistically | p99 | 9ms | 5ms | -4ms | -45.85
| ProductNoticesStore.View | p99 | 198ms | 108ms | -90ms | -45.55
| PostStore.GetSingle | p99 | 9ms | 5ms | -4ms | -45.00
| PluginStore.Get | p99 | 9ms | 5ms | -4ms | -42.55
| UserStore.IsEmpty | p99 | 15ms | 9ms | -6ms | -40.00
| ChannelStore.CreateInitialSidebarCategories | p99 | 165ms | 99ms | -66ms | -39.88
| PostStore.Update | p99 | 39ms | 24ms | -15ms | -38.09
| ChannelStore.SaveMember | p99 | 160ms | 99ms | -61ms | -38.03
| SessionStore.UpdateLastActivityAt | p99 | 16ms | 10ms | -6ms | -37.10
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 19ms | 12ms | -7ms | -37.10
| FileInfoStore.SetContent | p99 | 38ms | 24ms | -14ms | -36.92
| LinkMetadataStore.Get | p99 | 11ms | 7ms | -4ms | -36.69
| PluginStore.SetWithOptions | p99 | 35ms | 23ms | -12ms | -34.78
| PostStore.GetPostIdBeforeTime | p99 | 14ms | 9ms | -5ms | -34.62
| PostAcknowledgementStore.GetForPosts | p99 | 15ms | 10ms | -5ms | -32.75
| TeamStore.Get | p99 | 9ms | 6ms | -3ms | -32.59
| ThreadStore.GetThreadFollowers | p99 | 15ms | 10ms | -5ms | -32.40
| ChannelStore.CreateDirectChannel | p99 | 97ms | 66ms | -31ms | -32.04
| PluginStore.Delete | p99 | 16ms | 11ms | -5ms | -31.53
| ChannelStore.GetFileCount | p99 | 19ms | 13ms | -6ms | -30.88
| PostPersistentNotificationStore.GetSingle | p99 | 10ms | 7ms | -3ms | -30.85
| EmojiStore.GetByName | p99 | 10ms | 7ms | -3ms | -30.56
| StatusStore.UpdateLastActivityAt | p99 | 16ms | 11ms | -5ms | -30.45
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 14ms | 10ms | -4ms | -27.84
| UserStore.GetProfileByIds | p99 | 22ms | 16ms | -6ms | -27.69
| ThreadStore.GetMembershipForUser | p99 | 15ms | 11ms | -4ms | -26.10
| SessionStore.Save | p99 | 39ms | 29ms | -10ms | -25.91
| FileInfoStore.AttachToPost | p99 | 24ms | 18ms | -6ms | -25.52
| UserStore.UpdateFailedPasswordAttempts | p99 | 32ms | 24ms | -8ms | -25.11
| ChannelStore.GetGuestCount | p99 | 32ms | 24ms | -8ms | -24.87
| PostStore.Save | p99 | 49ms | 37ms | -12ms | -24.48
| UserStore.GetProfilesByUsernames | p99 | 16ms | 12ms | -4ms | -24.46
| DraftStore.Upsert | p99 | 21ms | 16ms | -5ms | -24.12
| DraftStore.Get | p99 | 12ms | 9ms | -3ms | -24.02
| PostStore.GetPostIdAfterTime | p99 | 21ms | 16ms | -5ms | -23.84
| SystemStore.GetByName | p99 | 21ms | 16ms | -5ms | -23.39
| FileInfoStore.GetForPost | p99 | 9ms | 7ms | -2ms | -22.76
| PreferenceStore.Get | p99 | 18ms | 14ms | -4ms | -22.34
| ChannelStore.UpdateLastViewedAt | p99 | 18ms | 14ms | -4ms | -21.77
| UserTermsOfServiceStore.GetByUser | p99 | 24ms | 19ms | -5ms | -20.94
| ChannelStore.GetChannels | p99 | 20ms | 16ms | -4ms | -20.06
| PreferenceStore.Save | p99 | 70ms | 56ms | -14ms | -19.98
| UserStore.AutocompleteUsersInChannel | p99 | 337ms | 276ms | -61ms | -18.12
| FileInfoStore.Save | p99 | 22ms | 18ms | -4ms | -17.83
| ChannelStore.GetMemberLastViewedAt | p99 | 23ms | 19ms | -4ms | -17.22
| SessionStore.Get | p99 | 48ms | 40ms | -8ms | -16.70
| TeamStore.GetTeamsByUserId | p99 | 24ms | 20ms | -4ms | -16.45
| PostPriorityStore.GetForPosts | p99 | 18ms | 15ms | -3ms | -16.43
| GroupStore.GetGroups | p99 | 20ms | 17ms | -3ms | -14.99
| AuditStore.Save | p99 | 27ms | 23ms | -4ms | -14.73
| StatusStore.Get | p99 | 20ms | 17ms | -3ms | -14.65
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 21ms | 18ms | -3ms | -14.37
| ChannelStore.IncrementMentionCount | p99 | 21ms | 18ms | -3ms | -14.25
| UserStore.GetAllProfiles | p99 | 22ms | 19ms | -3ms | -13.68
| PostStore.GetEtag | p99 | 22ms | 19ms | -3ms | -13.62
| TeamStore.GetAllPage | p99 | 23ms | 20ms | -3ms | -13.04
| ChannelStore.GetByName | p99 | 38ms | 33ms | -5ms | -12.99
| UserStore.GetAllProfilesInChannel | p99 | 840ms | 731ms | -109ms | -12.98
| ThreadStore.MaintainMembership | p99 | 23ms | 20ms | -3ms | -12.89
| ChannelStore.GetMember | p99 | 23ms | 20ms | -3ms | -12.80
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 24ms | 21ms | -3ms | -12.76
| UserStore.GetForLogin | p99 | 24ms | 21ms | -3ms | -12.70
| TeamStore.GetTeamsForUser | p99 | 24ms | 21ms | -3ms | -12.41
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 203ms | 178ms | -25ms | -12.35
| PostStore.GetPostsBefore | p99 | 21ms | 19ms | -2ms | -9.45
| ChannelStore.GetMemberCount | p99 | 74ms | 67ms | -7ms | -9.43
| SessionStore.GetLRUSessions | p99 | 22ms | 20ms | -2ms | -9.17
| ChannelStore.GetMemberForPost | p99 | 22ms | 20ms | -2ms | -9.09
| ChannelStore.GetMembersForUser | p99 | 22ms | 20ms | -2ms | -9.06
| ThreadStore.GetTotalUnreadThreads | p99 | 22ms | 20ms | -2ms | -8.99
| ThreadStore.GetTotalThreads | p99 | 22ms | 20ms | -2ms | -8.97
| ChannelStore.Get | p99 | 22ms | 20ms | -2ms | -8.94
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 23ms | 21ms | -2ms | -8.86
| PostStore.Get | p99 | 23ms | 21ms | -2ms | -8.67
| ThreadStore.GetTotalUnreadMentions | p99 | 23ms | 21ms | -2ms | -8.66
| UserStore.UpdateUpdateAt | p99 | 23ms | 21ms | -2ms | -8.62
| UserStore.UpdateLastLogin | p99 | 23ms | 21ms | -2ms | -8.54
| PostStore.GetPosts | p99 | 24ms | 22ms | -2ms | -8.32
| ThreadStore.GetTeamsUnreadForUser | p99 | 25ms | 23ms | -2ms | -8.12
| TeamStore.SaveMember | p99 | 93ms | 86ms | -7ms | -7.51
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 95ms | 89ms | -6ms | -6.30
| UserStore.Save | p99 | 217ms | 205ms | -12ms | -5.54
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 202ms | 192ms | -10ms | -4.96
| PostStore.SearchPostsForUser | p99 | 2.365s | 2.273s | -92ms | -3.89
| ChannelStore.UpdateSidebarCategories | p99 | 222ms | 214ms | -8ms | -3.61
| PostStore.GetPostsSince | p99 | 67ms | 65ms | -2ms | -2.98
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 11ms | 72ms | 61ms | 553.46
| getFileThumbnail | avg | 30ms | 34ms | 4ms | 13.25
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 47ms | 2.7s | 2.653s | 5590.71
| unfollowThreadByUser | p99 | 10ms | 24ms | 14ms | 140.70
| getPublicChannelsForTeam | p99 | 43ms | 48ms | 5ms | 11.55
| getFileThumbnail | p99 | 94ms | 99ms | 5ms | 5.34
| getTeamStats | p99 | 95ms | 99ms | 4ms | 4.21
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 3ms | 0s | -3ms | -103.26
| logout | avg | 56ms | 33ms | -23ms | -41.43
| patchPost | avg | 21ms | 16ms | -5ms | -23.30
| login | avg | 67ms | 53ms | -14ms | -20.86
| searchPostsInTeam | avg | 194ms | 155ms | -39ms | -20.10
| getAnalytics | avg | 32ms | 26ms | -6ms | -18.77
| updateCategoriesForTeamForUser | avg | 104ms | 91ms | -13ms | -12.52
| addTeamMember | avg | 811ms | 762ms | -49ms | -6.04
| createUser | avg | 125ms | 120ms | -5ms | -3.99
| createPost | avg | 290ms | 281ms | -9ms | -3.11
| addChannelMember | avg | 213ms | 207ms | -6ms | -2.81
| uploadFileStream | avg | 377ms | 367ms | -10ms | -2.65
| getProfileImage | avg | 80ms | 78ms | -2ms | -2.49
| removeUserCustomStatus | avg | 160ms | 157ms | -3ms | -1.87
| createDirectChannel | avg | 223ms | 219ms | -4ms | -1.79
| createChannel | avg | 210ms | 207ms | -3ms | -1.43
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| getChannel | p99 | 37ms | 10ms | -27ms | -73.47
| patchPost | p99 | 290ms | 80ms | -210ms | -72.42
| setPostReminder | p99 | 49ms | 25ms | -24ms | -49.48
| logout | p99 | 99ms | 50ms | -49ms | -49.41
| updateCategoriesForTeamForUser | p99 | 453ms | 238ms | -215ms | -47.51
| getTeamMember | p99 | 20ms | 11ms | -9ms | -45.83
| login | p99 | 424ms | 244ms | -180ms | -42.49
| getUsers | p99 | 40ms | 25ms | -15ms | -37.04
| getPostThread | p99 | 37ms | 24ms | -13ms | -35.14
| getPostsForChannelAroundLastUnread | p99 | 134ms | 88ms | -46ms | -34.37
| getUser | p99 | 44ms | 29ms | -15ms | -34.19
| getTeamMembersForUser | p99 | 35ms | 24ms | -11ms | -31.76
| autocompleteUsers | p99 | 287ms | 203ms | -84ms | -29.24
| deleteDraft | p99 | 14ms | 10ms | -4ms | -28.90
| getTeamsUnreadForUser | p99 | 38ms | 28ms | -10ms | -26.29
| getUsersByNames | p99 | 17ms | 13ms | -4ms | -23.93
| getChannelMember | p99 | 60ms | 46ms | -14ms | -23.22
| createPost | p99 | 1.27s | 980ms | -290ms | -22.84
| viewChannel | p99 | 50ms | 39ms | -11ms | -21.91
| getClientConfig | p99 | 52ms | 41ms | -11ms | -21.12
| getPostsForChannel | p99 | 162ms | 129ms | -33ms | -20.43
| upsertDraft | p99 | 23ms | 19ms | -4ms | -17.09
| getTeamsForUser | p99 | 24ms | 20ms | -4ms | -16.44
| getPreferences | p99 | 28ms | 24ms | -4ms | -14.54
| updatePreferences | p99 | 23ms | 20ms | -3ms | -13.13
| saveReaction | p99 | 47ms | 41ms | -6ms | -12.84
| getAllTeams | p99 | 25ms | 22ms | -3ms | -12.22
| getDrafts | p99 | 17ms | 15ms | -2ms | -11.43
| getChannelsForTeamForUser | p99 | 21ms | 19ms | -2ms | -9.35
| getChannelMembersForTeamForUser | p99 | 23ms | 21ms | -2ms | -8.82
| getThreadsForUser | p99 | 24ms | 22ms | -2ms | -8.48
| createUser | p99 | 473ms | 438ms | -35ms | -7.40
| getCategoriesForTeamForUser | p99 | 96ms | 90ms | -6ms | -6.25
| updateReadStateThreadByUser | p99 | 94ms | 89ms | -5ms | -5.30
| createGroupChannel | p99 | 903ms | 878ms | -25ms | -2.77
| searchPostsInTeam | p99 | 2.367s | 2.314s | -53ms | -2.24
| addTeamMember | p99 | 2.439s | 2.407s | -32ms | -1.31
| removeUserCustomStatus | p99 | 475ms | 470ms | -5ms | -1.05
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 23ms | -4ms | -14.734
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -59.255
| |  P99| 22ms| 9ms | -13ms | -57.906
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 74ms| 72ms | -2ms | -2.710
| |  P99| 202ms| 192ms | -10ms | -4.958
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 18ms | -3ms | -14.372
| ChannelStore.AnalyticsTypeCount |  Avg| 7ms| 10ms | 3ms | 40.014
| |  P99| 24ms| 25ms | 1ms | 4.246
| ChannelStore.Autocomplete |  Avg| 44ms| 45ms | 1ms | 2.287
| |  P99| 99ms| 100ms | 1ms | 1.005
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 11ms| 72ms | 61ms | 556.391
| |  P99| 47ms| 2.7s | 2.653s | 5590.712
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 11ms | -3ms | -21.898
| |  P99| 97ms| 66ms | -31ms | -32.043
| ChannelStore.CreateInitialSidebarCategories |  Avg| 36ms| 34ms | -2ms | -5.518
| |  P99| 165ms| 99ms | -66ms | -39.885
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.945
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 26ms| 42ms | 16ms | 62.440
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.128
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 17ms | -3ms | -15.292
| |  P99| 203ms| 178ms | -25ms | -12.345
| ChannelStore.GetByName |  Avg| 4ms| 3ms | -1ms | -27.635
| |  P99| 38ms| 33ms | -5ms | -12.991
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 16ms | -4ms | -20.061
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 8ms | -8ms | -51.450
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -27.835
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 13ms | -6ms | -30.881
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 32ms| 24ms | -8ms | -24.872
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.802
| ChannelStore.GetMemberCount |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 74ms| 67ms | -7ms | -9.426
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.086
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 23ms| 19ms | -4ms | -17.217
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.063
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 21ms | 11ms | 110.614
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.310
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 95ms| 89ms | -6ms | -6.299
| ChannelStore.GetSidebarCategory |  Avg| 18ms| 15ms | -3ms | -17.125
| |  P99| 193ms| 77ms | -116ms | -60.101
| ChannelStore.GetTeamChannels |  Avg| 20ms| 17ms | -3ms | -15.172
| |  P99| 95ms| 49ms | -46ms | -48.421
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 1ms | -1ms | -66.549
| |  P99| 21ms| 18ms | -3ms | -14.251
| ChannelStore.Save |  Avg| 9ms| 7ms | -2ms | -21.351
| |  P99| 145ms| 30ms | -115ms | -79.314
| ChannelStore.SaveMember |  Avg| 27ms| 25ms | -2ms | -7.506
| |  P99| 160ms| 99ms | -61ms | -38.031
| ChannelStore.SearchGroupChannels |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 34ms| 35ms | 1ms | 2.910
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 14ms | -4ms | -21.769
| ChannelStore.UpdateSidebarCategories |  Avg| 67ms| 61ms | -6ms | -8.952
| |  P99| 222ms| 214ms | -8ms | -3.612
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 2ms | -1ms | -33.999
| |  P99| 39ms| 13ms | -26ms | -66.882
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 2ms| 6ms | 4ms | 160.162
| |  P99| 7ms| 279ms | 272ms | 3751.724
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.267
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 3ms | -1ms | -27.776
| |  P99| 10ms| 5ms | -5ms | -51.811
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -24.017
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.173
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -24.118
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.560
| EmojiStore.GetMultipleByName |  Avg| 0s| 1ms | 1ms | 202.452
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 4ms | -1ms | -19.643
| |  P99| 24ms| 18ms | -6ms | -25.516
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.167
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 18ms | 12ms | 188.992
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.757
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 18ms | -4ms | -17.834
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 38ms| 24ms | -14ms | -36.921
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 12ms | -7ms | -37.098
| GroupStore.GetByName |  Avg| 2ms| 1ms | -1ms | -63.760
| |  P99| 24ms| 23ms | -1ms | -4.107
| GroupStore.GetGroups |  Avg| 2ms| 1ms | -1ms | -65.459
| |  P99| 20ms| 17ms | -3ms | -14.986
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 35ms| 14ms | -21ms | -60.432
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 35ms | 14ms | 68.044
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 145.077
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.845
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 130.719
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 2ms | -1ms | -32.355
| |  P99| 21ms| 5ms | -16ms | -74.505
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 7ms | -4ms | -36.691
| LinkMetadataStore.Save |  Avg| 5ms| 2ms | -3ms | -56.162
| |  P99| 47ms| 5ms | -42ms | -89.679
| PluginStore.Delete |  Avg| 2ms| 1ms | -1ms | -66.199
| |  P99| 16ms| 11ms | -5ms | -31.530
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.554
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 23ms | -12ms | -34.777
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 17ms | 11ms | 169.895
| PostAcknowledgementStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -32.753
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.850
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 340.998
| PostPriorityStore.GetForPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.434
| PostStore.AnalyticsPostCount |  Avg| 222ms| 233ms | 11ms | 4.950
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.Delete |  Avg| 7ms| 8ms | 1ms | 14.410
| |  P99| 10ms| 23ms | 13ms | 130.613
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.670
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.620
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 1ms | -1ms | -62.470
| |  P99| 21ms| 16ms | -5ms | -23.842
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -34.620
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 2ms | -1ms | -29.160
| |  P99| 24ms| 5ms | -19ms | -78.838
| PostStore.GetPostReminders |  Avg| 6ms| 3ms | -3ms | -46.958
| |  P99| 46ms| 22ms | -24ms | -52.459
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.319
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 19ms | -2ms | -9.451
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 67ms| 65ms | -2ms | -2.981
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.001
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 8ms | -1ms | -11.688
| |  P99| 49ms| 37ms | -12ms | -24.483
| PostStore.SearchPostsForUser |  Avg| 190ms| 150ms | -40ms | -21.060
| |  P99| 2.365s| 2.273s | -92ms | -3.890
| PostStore.SetPostReminder |  Avg| 6ms| 3ms | -3ms | -49.656
| |  P99| 24ms| 9ms | -15ms | -62.240
| PostStore.Update |  Avg| 11ms| 9ms | -2ms | -18.560
| |  P99| 39ms| 24ms | -15ms | -38.094
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 14ms | -4ms | -22.337
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.062
| PreferenceStore.Save |  Avg| 7ms| 6ms | -1ms | -13.581
| |  P99| 70ms| 56ms | -14ms | -19.980
| ProductNoticesStore.ClearOldNotices |  Avg| 19ms| 18ms | -1ms | -5.348
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 22ms| 19ms | -3ms | -13.847
| |  P99| 198ms| 108ms | -90ms | -45.551
| ReactionStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 11ms | 4ms | 54.375
| RetentionPolicyStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RetentionPolicyStore.GetCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -73.111
| RoleStore.GetByNames |  Avg| 2ms| 1ms | -1ms | -61.965
| |  P99| 23ms| 5ms | -18ms | -77.756
| SessionStore.Get |  Avg| 4ms| 3ms | -1ms | -24.646
| |  P99| 48ms| 40ms | -8ms | -16.704
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.165
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 29ms | -10ms | -25.909
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.102
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 17ms | -3ms | -14.651
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 19.054
| StatusStore.SaveOrUpdate |  Avg| 16ms| 25ms | 9ms | 57.444
| |  P99| 233ms| 431ms | 198ms | 85.153
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 2ms | -1ms | -35.553
| |  P99| 46ms| 22ms | -24ms | -52.459
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 11ms | -5ms | -30.450
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 16ms | -5ms | -23.387
| SystemStore.Save |  Avg| 2ms| 0s | -2ms | -94.866
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 6ms | -3ms | -32.589
| TeamStore.GetActiveMemberCount |  Avg| 52ms| 53ms | 1ms | 1.918
| |  P99| 95ms| 99ms | 4ms | 4.210
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -13.045
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.761
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.499
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 1ms | -1ms | -60.428
| |  P99| 24ms| 20ms | -4ms | -16.447
| TeamStore.GetTeamsForUser |  Avg| 2ms| 1ms | -1ms | -58.018
| |  P99| 24ms| 21ms | -3ms | -12.413
| TeamStore.GetTotalMemberCount |  Avg| 52ms| 26ms | -26ms | -50.007
| |  P99| 95ms| 50ms | -45ms | -47.368
| TeamStore.SaveMember |  Avg| 28ms| 25ms | -3ms | -10.826
| |  P99| 93ms| 86ms | -7ms | -7.512
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.404
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -26.105
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 2ms | -1ms | -38.243
| |  P99| 25ms| 23ms | -2ms | -8.122
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -32.403
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.060
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.700
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.965
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.662
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.988
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.858
| ThreadStore.MaintainMembership |  Avg| 4ms| 3ms | -1ms | -28.465
| |  P99| 23ms| 20ms | -3ms | -12.889
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 0s | -3ms | -107.210
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 2ms | -1ms | -38.572
| |  P99| 10ms| 9ms | -1ms | -10.019
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.403
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.543
| UserStore.AnalyticsActiveCount |  Avg| 18ms| 19ms | 1ms | 5.418
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 0s| 1ms | 1ms | 205.996
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 45ms| 43ms | -2ms | -4.409
| |  P99| 337ms| 276ms | -61ms | -18.116
| UserStore.Count |  Avg| 13ms| 14ms | 1ms | 7.662
| |  P99| 25ms| 43ms | 18ms | 72.454
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.683
| UserStore.GetAllProfilesInChannel |  Avg| 232ms| 226ms | -6ms | -2.584
| |  P99| 840ms| 731ms | -109ms | -12.981
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -51.744
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 21ms | -3ms | -12.700
| UserStore.GetMany |  Avg| 1ms| 3ms | 2ms | 266.954
| |  P99| 5ms| 44ms | 39ms | 787.879
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 1ms | -1ms | -59.964
| |  P99| 22ms| 16ms | -6ms | -27.695
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 1ms | -1ms | -65.361
| |  P99| 16ms| 12ms | -4ms | -24.463
| UserStore.GetProfilesInChannel |  Avg| 16ms| 13ms | -3ms | -18.459
| |  P99| 49ms| 25ms | -24ms | -49.357
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 5ms | -18ms | -76.596
| UserStore.GetUnreadCount |  Avg| 2ms| 1ms | -1ms | -63.798
| |  P99| 13ms| 14ms | 1ms | 7.731
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 9ms | -6ms | -40.000
| UserStore.Save |  Avg| 72ms| 70ms | -2ms | -2.791
| |  P99| 217ms| 205ms | -12ms | -5.537
| UserStore.Search |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.861
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 3ms | -1ms | -25.544
| |  P99| 32ms| 24ms | -8ms | -25.106
| UserStore.UpdateLastLogin |  Avg| 5ms| 4ms | -1ms | -21.006
| |  P99| 23ms| 21ms | -2ms | -8.540
| UserStore.UpdateUpdateAt |  Avg| 5ms| 4ms | -1ms | -21.054
| |  P99| 23ms| 21ms | -2ms | -8.615
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 24ms| 19ms | -5ms | -20.945
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 34ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 213ms| 207ms | -6ms | -2.813
| | P99| 492ms| 490ms | -2ms | -0.407
| addTeamMember | Avg| 811ms| 762ms | -49ms | -6.041
| | P99| 2.439s| 2.407s | -32ms | -1.312
| autocompleteChannelsForTeamForSearch | Avg| 11ms| 72ms | 61ms | 553.461
| | P99| 47ms| 2.7s | 2.653s | 5590.712
| autocompleteUsers | Avg| 41ms| 40ms | -1ms | -2.424
| | P99| 287ms| 203ms | -84ms | -29.244
| createChannel | Avg| 210ms| 207ms | -3ms | -1.428
| | P99| 487ms| 488ms | 1ms | 0.205
| createDirectChannel | Avg| 223ms| 219ms | -4ms | -1.793
| | P99| 494ms| 493ms | -1ms | -0.203
| createGroupChannel | Avg| 329ms| 329ms | 0s | 0.000
| | P99| 903ms| 878ms | -25ms | -2.768
| createPost | Avg| 290ms| 281ms | -9ms | -3.107
| | P99| 1.27s| 980ms | -290ms | -22.836
| createUser | Avg| 125ms| 120ms | -5ms | -3.988
| | P99| 473ms| 438ms | -35ms | -7.396
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 14ms| 10ms | -4ms | -28.903
| deletePost | Avg| 10ms| 11ms | 1ms | 9.864
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 23ms| 24ms | 1ms | 4.283
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 22ms | -3ms | -12.222
| getAnalytics | Avg| 32ms| 26ms | -6ms | -18.765
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 30ms| 29ms | -1ms | -3.388
| | P99| 96ms| 90ms | -6ms | -6.248
| getChannel | Avg| 4ms| 3ms | -1ms | -28.340
| | P99| 37ms| 10ms | -27ms | -73.472
| getChannelMember | Avg| 6ms| 5ms | -1ms | -17.327
| | P99| 60ms| 46ms | -14ms | -23.224
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.822
| getChannelMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 45ms| 44ms | -1ms | -2.222
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 19ms | -2ms | -9.350
| getChannelsForUser | Avg| 3ms| 2ms | -1ms | -36.655
| | P99| 23ms| 22ms | -1ms | -4.262
| getClientConfig | Avg| 4ms| 3ms | -1ms | -24.156
| | P99| 52ms| 41ms | -11ms | -21.118
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 15ms | -2ms | -11.429
| getFilePreview | Avg| 45ms| 44ms | -1ms | -2.232
| | P99| 216ms| 214ms | -2ms | -0.925
| getFileThumbnail | Avg| 30ms| 34ms | 4ms | 13.247
| | P99| 94ms| 99ms | 5ms | 5.337
| getFilteredUsersStats | Avg| 13ms| 12ms | -1ms | -7.714
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 5ms| 4ms | -1ms | -21.893
| | P99| 37ms| 24ms | -13ms | -35.144
| getPostsForChannel | Avg| 16ms| 15ms | -1ms | -6.290
| | P99| 162ms| 129ms | -33ms | -20.429
| getPostsForChannelAroundLastUnread | Avg| 12ms| 11ms | -1ms | -8.174
| | P99| 134ms| 88ms | -46ms | -34.367
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 24ms | -4ms | -14.541
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 80ms| 78ms | -2ms | -2.489
| | P99| 403ms| 400ms | -3ms | -0.745
| getPublicChannelsForTeam | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 43ms| 48ms | 5ms | 11.550
| getRolesByNames | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 1ms | -1ms | -56.781
| | P99| 20ms| 11ms | -9ms | -45.832
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 35ms| 24ms | -11ms | -31.764
| getTeamStats | Avg| 52ms| 53ms | 1ms | 1.911
| | P99| 95ms| 99ms | 4ms | 4.210
| getTeamsForUser | Avg| 2ms| 1ms | -1ms | -58.063
| | P99| 24ms| 20ms | -4ms | -16.438
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 38ms| 28ms | -10ms | -26.291
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.482
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 44ms| 29ms | -15ms | -34.191
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 4ms | -1ms | -22.103
| | P99| 40ms| 25ms | -15ms | -37.039
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 13ms | -4ms | -23.935
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 67ms| 53ms | -14ms | -20.859
| | P99| 424ms| 244ms | -180ms | -42.492
| logout | Avg| 56ms| 33ms | -23ms | -41.429
| | P99| 99ms| 50ms | -49ms | -49.411
| patchPost | Avg| 21ms| 16ms | -5ms | -23.300
| | P99| 290ms| 80ms | -210ms | -72.419
| removeUserCustomStatus | Avg| 160ms| 157ms | -3ms | -1.870
| | P99| 475ms| 470ms | -5ms | -1.052
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 47ms| 41ms | -6ms | -12.836
| searchAllChannels | Avg| 44ms| 45ms | 1ms | 2.276
| | P99| 99ms| 100ms | 1ms | 1.005
| searchGroupChannels | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 34ms| 35ms | 1ms | 2.910
| searchPostsInTeam | Avg| 194ms| 155ms | -39ms | -20.098
| | P99| 2.367s| 2.314s | -53ms | -2.239
| searchUsers | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 13ms| 12ms | -1ms | -7.531
| | P99| 49ms| 25ms | -24ms | -49.482
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 8ms| 9ms | 1ms | 13.245
| | P99| 10ms| 24ms | 14ms | 140.704
| updateCategoriesForTeamForUser | Avg| 104ms| 91ms | -13ms | -12.520
| | P99| 453ms| 238ms | -215ms | -47.513
| updatePreferences | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 20ms | -3ms | -13.135
| updateReadStateAllThreadsByUser | Avg| 3ms| 0s | -3ms | -103.256
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 94ms| 89ms | -5ms | -5.301
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 377ms| 367ms | -10ms | -2.649
| | P99| 987ms| 985ms | -2ms | -0.203
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 19ms | -4ms | -17.087
| viewChannel | Avg| 7ms| 6ms | -1ms | -14.931
| | P99| 50ms| 39ms | -11ms | -21.913
