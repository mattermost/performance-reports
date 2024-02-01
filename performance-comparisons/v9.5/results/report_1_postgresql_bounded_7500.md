### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | avg | 1ms | 28ms | 27ms | 2664.47
| PluginStore.List | avg | 1ms | 3ms | 2ms | 168.03
| PostStore.GetPostsAfter | avg | 2ms | 4ms | 2ms | 85.59
| PreferenceStore.DeleteCategoryAndName | avg | 4ms | 7ms | 3ms | 70.26
| PostStore.GetPostReminders | avg | 3ms | 5ms | 2ms | 57.24
| PostStore.SetPostReminder | avg | 4ms | 6ms | 2ms | 54.68
| StatusStore.SaveOrUpdate | avg | 39ms | 55ms | 16ms | 40.61
| UserStore.AnalyticsActiveCount | avg | 23ms | 27ms | 4ms | 17.64
| ChannelStore.UpdateSidebarCategories | avg | 32ms | 35ms | 3ms | 9.52
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | p99 | 5ms | 99ms | 94ms | 1898.11
| PostStore.GetPostsAfter | p99 | 7ms | 69ms | 62ms | 898.48
| PluginStore.List | p99 | 14ms | 77ms | 63ms | 438.88
| PostStore.SetPostReminder | p99 | 9ms | 48ms | 39ms | 419.17
| JobStore.GetCountByStatusAndType | p99 | 18ms | 66ms | 48ms | 264.10
| ComplianceStore.MessageExport | p99 | 10ms | 36ms | 26ms | 252.43
| JobStore.GetAllByTypePage | p99 | 5ms | 16ms | 11ms | 222.22
| UserStore.GetMany | p99 | 9ms | 23ms | 14ms | 147.37
| PostStore.GetPostReminders | p99 | 9ms | 22ms | 13ms | 142.08
| JobStore.Save | p99 | 8ms | 19ms | 11ms | 141.94
| ChannelStore.UpdateSidebarCategories | p99 | 96ms | 220ms | 124ms | 129.00
| JobStore.GetNewestJobByStatusesAndType | p99 | 8ms | 17ms | 9ms | 111.11
| PreferenceStore.DeleteCategoryAndName | p99 | 45ms | 95ms | 50ms | 109.89
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 10ms | 5ms | 101.01
| PostAcknowledgementStore.GetForPost | p99 | 14ms | 22ms | 8ms | 56.34
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 9ms | 13ms | 4ms | 42.14
| ChannelStore.Save | p99 | 32ms | 45ms | 13ms | 40.62
| FileInfoStore.Save | p99 | 22ms | 28ms | 6ms | 27.75
| UserStore.GetByUsername | p99 | 18ms | 22ms | 4ms | 22.23
| UserStore.Get | p99 | 14ms | 17ms | 3ms | 22.09
| ChannelStore.SearchGroupChannels | p99 | 25ms | 30ms | 5ms | 20.36
| PreferenceStore.GetAll | p99 | 25ms | 30ms | 5ms | 20.07
| ReactionStore.GetForPost | p99 | 16ms | 19ms | 3ms | 18.60
| ReactionStore.ExistsOnPost | p99 | 17ms | 20ms | 3ms | 17.36
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 36ms | 42ms | 6ms | 16.84
| ChannelStore.GetAllChannelMembersForUser | p99 | 12ms | 14ms | 2ms | 16.64
| ChannelStore.CreateDirectChannel | p99 | 76ms | 88ms | 12ms | 15.69
| ChannelStore.GetMember | p99 | 21ms | 24ms | 3ms | 14.42
| ThreadStore.GetThreadFollowers | p99 | 16ms | 18ms | 2ms | 12.19
| PluginStore.Get | p99 | 18ms | 20ms | 2ms | 10.94
| ThreadStore.GetMembershipForUser | p99 | 18ms | 20ms | 2ms | 10.90
| GroupStore.GetByName | p99 | 23ms | 25ms | 2ms | 8.70
| PostStore.GetPosts | p99 | 28ms | 30ms | 2ms | 7.16
| WebhookStore.GetOutgoingByTeam | p99 | 30ms | 32ms | 2ms | 6.77
| ChannelStore.CreateInitialSidebarCategories | p99 | 92ms | 97ms | 5ms | 5.46
| PostStore.GetPostReminderMetadata | p99 | 43ms | 45ms | 2ms | 4.62
| UserStore.GetProfilesInChannel | p99 | 395ms | 405ms | 10ms | 2.53
| ChannelStore.SaveMember | p99 | 157ms | 159ms | 2ms | 1.27
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMemberOnly | avg | 2ms | 0s | -2ms | -125.83
| LicenseStore.GetAll | avg | 2ms | 0s | -2ms | -118.39
| ChannelStore.GetMemberCountsByGroup | avg | 4ms | 0s | -4ms | -101.69
| ProductNoticesStore.ClearOldNotices | avg | 26ms | 0s | -26ms | -101.20
| PostStore.AnalyticsPostCount | avg | 225ms | 13ms | -212ms | -94.17
| RetentionPolicyStore.GetAll | avg | 5ms | 1ms | -4ms | -82.86
| DraftStore.GetDraftsForUser | avg | 3ms | 1ms | -2ms | -70.40
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 82ms | 70ms | -12ms | -14.62
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 25ms | 23ms | -2ms | -8.08
| PostStore.SearchPostsForUser | avg | 157ms | 154ms | -3ms | -1.91
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 50ms | 0s | -50ms | -100.46
| ChannelStore.GetMemberCountsByGroup | p99 | 44ms | 0s | -44ms | -100.00
| ChannelStore.GetMemberOnly | p99 | 22ms | 0s | -22ms | -98.30
| PostStore.AnalyticsPostCount | p99 | 495ms | 25ms | -470ms | -94.95
| JobStore.UpdateStatusOptimistically | p99 | 38ms | 5ms | -33ms | -85.71
| LicenseStore.GetAll | p99 | 23ms | 5ms | -18ms | -79.12
| RetentionPolicyStore.GetAll | p99 | 24ms | 5ms | -19ms | -77.87
| ChannelStore.GetChannelUnread | p99 | 19ms | 5ms | -14ms | -74.27
| ChannelStore.GetChannelsByUser | p99 | 33ms | 9ms | -24ms | -72.18
| RoleStore.ChannelHigherScopedPermissions | p99 | 44ms | 19ms | -25ms | -56.50
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 10ms | 5ms | -5ms | -51.28
| DraftStore.GetDraftsForUser | p99 | 10ms | 5ms | -5ms | -51.25
| ProductNoticesStore.GetViews | p99 | 10ms | 5ms | -5ms | -50.60
| ChannelStore.Autocomplete | p99 | 181ms | 100ms | -81ms | -44.87
| ThreadStore.MarkAllAsReadByChannels | p99 | 9ms | 5ms | -4ms | -44.20
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -43.48
| JobStore.UpdateStatus | p99 | 8ms | 5ms | -3ms | -38.96
| UserStore.Count | p99 | 76ms | 47ms | -29ms | -38.15
| PostStore.Update | p99 | 39ms | 25ms | -14ms | -35.90
| PostPersistentNotificationStore.GetSingle | p99 | 14ms | 9ms | -5ms | -34.69
| TeamStore.GetByName | p99 | 13ms | 9ms | -4ms | -31.37
| ThreadStore.MarkAsRead | p99 | 13ms | 9ms | -4ms | -31.05
| PostAcknowledgementStore.GetForPosts | p99 | 21ms | 15ms | -6ms | -28.09
| StatusStore.SaveOrUpdate | p99 | 659ms | 496ms | -163ms | -24.74
| FileInfoStore.Get | p99 | 13ms | 10ms | -3ms | -22.47
| PostPriorityStore.GetForPosts | p99 | 23ms | 18ms | -5ms | -21.87
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 232ms | 182ms | -50ms | -21.53
| FileInfoStore.SetContent | p99 | 30ms | 24ms | -6ms | -20.25
| JobStore.GetAllByStatus | p99 | 28ms | 23ms | -5ms | -18.14
| ReactionStore.Save | p99 | 39ms | 32ms | -7ms | -18.11
| JobStore.Get | p99 | 30ms | 25ms | -5ms | -16.81
| LinkMetadataStore.Get | p99 | 14ms | 12ms | -2ms | -14.26
| ThreadStore.GetTeamsUnreadForUser | p99 | 28ms | 24ms | -4ms | -14.06
| ChannelStore.AutocompleteInTeamForSearch | p99 | 210ms | 182ms | -28ms | -13.31
| UserStore.Update | p99 | 43ms | 38ms | -5ms | -11.54
| ThreadStore.GetThreadForUser | p99 | 28ms | 25ms | -3ms | -10.54
| PostStore.Get | p99 | 30ms | 27ms | -3ms | -9.98
| ChannelStore.GetFileCount | p99 | 22ms | 20ms | -2ms | -8.89
| ChannelStore.GetChannels | p99 | 23ms | 21ms | -2ms | -8.88
| StatusStore.GetByIds | p99 | 23ms | 21ms | -2ms | -8.72
| ChannelStore.GetGuestCount | p99 | 33ms | 31ms | -2ms | -6.13
| ChannelStore.GetPublicChannelsForTeam | p99 | 45ms | 43ms | -2ms | -4.47
| UserStore.AutocompleteUsersInChannel | p99 | 325ms | 313ms | -12ms | -3.70
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 99ms | 96ms | -3ms | -3.04
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 83ms | 81ms | -2ms | -2.40
| ChannelStore.GetMemberCount | p99 | 85ms | 83ms | -2ms | -2.36
| ProductNoticesStore.View | p99 | 217ms | 212ms | -5ms | -2.31
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteDraft | avg | 1ms | 3ms | 2ms | 149.04
| patchPost | avg | 49ms | 77ms | 28ms | 57.44
| setPostReminder | avg | 16ms | 19ms | 3ms | 18.43
| updateCategoriesForTeamForUser | avg | 46ms | 51ms | 5ms | 10.91
| autocompleteChannelsForTeamForSearch | avg | 25ms | 27ms | 2ms | 7.87
| createPost | avg | 286ms | 305ms | 19ms | 6.64
| uploadFileStream | avg | 409ms | 427ms | 18ms | 4.40
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | p99 | 235ms | 2.335s | 2.1s | 895.51
| deletePost | p99 | 25ms | 48ms | 23ms | 92.59
| getJobsByType | p99 | 10ms | 16ms | 6ms | 62.18
| getChannel | p99 | 23ms | 37ms | 14ms | 61.95
| createGroupChannel | p99 | 987ms | 1.27s | 283ms | 28.68
| getChannelMember | p99 | 29ms | 35ms | 6ms | 20.42
| searchGroupChannels | p99 | 25ms | 30ms | 5ms | 20.35
| getPreferences | p99 | 27ms | 32ms | 5ms | 18.32
| getClientConfig | p99 | 48ms | 53ms | 5ms | 10.50
| logout | p99 | 92ms | 98ms | 6ms | 6.52
| getTeamMembersForUser | p99 | 31ms | 33ms | 2ms | 6.38
| getFilePreview | p99 | 195ms | 205ms | 10ms | 5.13
| setPostReminder | p99 | 93ms | 95ms | 2ms | 2.15
| getAnalytics | p99 | 96ms | 98ms | 2ms | 2.09
| getFileThumbnail | p99 | 98ms | 100ms | 2ms | 2.04
| createUser | p99 | 250ms | 255ms | 5ms | 2.00
| login | p99 | 416ms | 424ms | 8ms | 1.92
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 5ms | 0s | -5ms | -101.80
| getOnboarding | avg | 5ms | 0s | -5ms | -99.00
| getThreadForUser | avg | 10ms | 0s | -10ms | -96.29
| getRolesByNames | avg | 2ms | 0s | -2ms | -94.58
| getDrafts | avg | 4ms | 1ms | -3ms | -84.58
| getChannelsForUser | avg | 10ms | 4ms | -6ms | -60.18
| getProfileImage | avg | 85ms | 63ms | -22ms | -25.74
| getSelfHostedProducts | avg | 18ms | 15ms | -3ms | -16.29
| createDirectChannel | avg | 334ms | 285ms | -49ms | -14.65
| getPostsForChannelAroundLastUnread | avg | 22ms | 19ms | -3ms | -13.41
| getPostsForChannel | avg | 19ms | 17ms | -2ms | -10.72
| getConfig | avg | 30ms | 28ms | -2ms | -6.69
| getLicenseSelfServeStatus | avg | 61ms | 57ms | -4ms | -6.60
| removeUserCustomStatus | avg | 201ms | 188ms | -13ms | -6.45
| addChannelMember | avg | 273ms | 263ms | -10ms | -3.67
| searchPostsInTeam | avg | 164ms | 159ms | -5ms | -3.04
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getThreadForUser | p99 | 25ms | 0s | -25ms | -100.60
| getOnboarding | p99 | 10ms | 0s | -10ms | -100.50
| channelMemberCountsByGroup | p99 | 47ms | 0s | -47ms | -99.76
| getRolesByNames | p99 | 44ms | 5ms | -39ms | -87.64
| getPrevTrialLicense | p99 | 23ms | 5ms | -18ms | -77.08
| getChannelUnread | p99 | 19ms | 5ms | -14ms | -74.27
| getChannelsForUser | p99 | 197ms | 72ms | -125ms | -63.53
| getConfig | p99 | 218ms | 97ms | -121ms | -55.38
| getSelfHostedProducts | p99 | 99ms | 49ms | -50ms | -50.76
| getDrafts | p99 | 10ms | 5ms | -5ms | -50.74
| getProductNotices | p99 | 10ms | 5ms | -5ms | -50.47
| searchAllChannels | p99 | 181ms | 100ms | -81ms | -44.87
| updatePreferences | p99 | 36ms | 24ms | -12ms | -33.61
| unfollowThreadByUser | p99 | 69ms | 46ms | -23ms | -33.58
| addChannelMember | p99 | 677ms | 496ms | -181ms | -26.72
| getPostsForChannelAroundLastUnread | p99 | 397ms | 291ms | -106ms | -26.71
| removeUserCustomStatus | p99 | 605ms | 489ms | -116ms | -19.17
| autocompleteChannelsForTeamForSearch | p99 | 210ms | 182ms | -28ms | -13.31
| getPostThread | p99 | 60ms | 53ms | -7ms | -11.69
| getAllTeams | p99 | 28ms | 25ms | -3ms | -10.90
| getPostsForChannel | p99 | 193ms | 174ms | -19ms | -9.84
| getTeamsUnreadForUser | p99 | 43ms | 39ms | -4ms | -9.29
| updateReadStateThreadByUser | p99 | 141ms | 129ms | -12ms | -8.49
| createDirectChannel | p99 | 984ms | 911ms | -73ms | -7.42
| createPost | p99 | 1.391s | 1.293s | -98ms | -7.04
| autocompleteUsers | p99 | 236ms | 222ms | -14ms | -5.94
| saveReaction | p99 | 104ms | 99ms | -5ms | -4.82
| updateCategoriesForTeamForUser | p99 | 227ms | 220ms | -7ms | -3.09
| getProfileImage | p99 | 460ms | 451ms | -9ms | -1.96
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.499
| BotStore.Save |  Avg| 2ms| 3ms | 1ms | 41.340
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 82ms| 70ms | -12ms | -14.623
| |  P99| 232ms| 182ms | -50ms | -21.528
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.799
| ChannelStore.AnalyticsTypeCount |  Avg| 9ms| 10ms | 1ms | 11.091
| |  P99| 24ms| 25ms | 1ms | 4.095
| ChannelStore.Autocomplete |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 181ms| 100ms | -81ms | -44.865
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 25ms| 26ms | 1ms | 3.942
| |  P99| 210ms| 182ms | -28ms | -13.307
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 15ms | 1ms | 7.221
| |  P99| 76ms| 88ms | 12ms | 15.688
| ChannelStore.CreateInitialSidebarCategories |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 92ms| 97ms | 5ms | 5.461
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.730
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 36ms| 42ms | 6ms | 16.842
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.643
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 25ms| 23ms | -2ms | -8.084
| |  P99| 99ms| 96ms | -3ms | -3.044
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 32ms | 0s | 0.000
| ChannelStore.GetByNameIncludeDeleted |  Avg| 1ms| 0s | -1ms | -156.636
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.268
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.879
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 3ms | -1ms | -24.263
| |  P99| 33ms| 9ms | -24ms | -72.180
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -8.892
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 31ms | -2ms | -6.131
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.418
| ChannelStore.GetMemberCount |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 85ms| 83ms | -2ms | -2.358
| ChannelStore.GetMemberCountsByGroup |  Avg| 4ms| 0s | -4ms | -101.693
| |  P99| 44ms| 0s | -44ms | -100.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.422
| ChannelStore.GetMemberOnly |  Avg| 2ms| 0s | -2ms | -125.828
| |  P99| 22ms| 0s | -22ms | -98.303
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 19ms| 20ms | 1ms | 5.312
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.503
| ChannelStore.GetPublicChannelsForTeam |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.468
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 83ms| 81ms | -2ms | -2.404
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 7ms | 1ms | 15.795
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 1ms | -1ms | -66.518
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 7ms| 8ms | 1ms | 14.491
| |  P99| 32ms| 45ms | 13ms | 40.623
| ChannelStore.SaveMember |  Avg| 27ms| 28ms | 1ms | 3.678
| |  P99| 157ms| 159ms | 2ms | 1.270
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 29.923
| |  P99| 25ms| 30ms | 5ms | 20.360
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 32ms| 35ms | 3ms | 9.518
| |  P99| 96ms| 220ms | 124ms | 128.999
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| CommandWebhookStore.Cleanup |  Avg| 1ms| 28ms | 27ms | 2664.465
| |  P99| 5ms| 99ms | 94ms | 1898.112
| ComplianceStore.MessageExport |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 36ms | 26ms | 252.427
| DraftStore.Delete |  Avg| 2ms| 1ms | -1ms | -64.452
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 2ms | 1ms | 129.053
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 3ms| 1ms | -2ms | -70.403
| |  P99| 10ms| 5ms | -5ms | -51.245
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.980
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 10ms | -3ms | -22.472
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 28ms | 6ms | 27.752
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 30ms| 24ms | -6ms | -20.253
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.053
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 25ms | 2ms | 8.704
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.730
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 1ms | -1ms | -45.172
| |  P99| 10ms| 5ms | -5ms | -51.282
| JobStore.Get |  Avg| 2ms| 1ms | -1ms | -61.354
| |  P99| 30ms| 25ms | -5ms | -16.807
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 28ms| 23ms | -5ms | -18.140
| JobStore.GetAllByTypePage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 16ms | 11ms | 222.222
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 2ms | 1ms | 74.570
| |  P99| 18ms| 66ms | 48ms | 264.099
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 1ms | -1ms | -57.225
| |  P99| 8ms| 17ms | 9ms | 111.112
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 19ms | 11ms | 141.935
| JobStore.UpdateOptimistically |  Avg| 2ms| 3ms | 1ms | 44.859
| |  P99| 6ms| 6ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.961
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 3ms | -1ms | -28.325
| |  P99| 38ms| 5ms | -33ms | -85.714
| LicenseStore.GetAll |  Avg| 2ms| 0s | -2ms | -118.388
| |  P99| 23ms| 5ms | -18ms | -79.121
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.262
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PluginStore.Delete |  Avg| 1ms| 2ms | 1ms | 66.981
| |  P99| 15ms| 16ms | 1ms | 6.690
| PluginStore.Get |  Avg| 1ms| 2ms | 1ms | 71.852
| |  P99| 18ms| 20ms | 2ms | 10.937
| PluginStore.List |  Avg| 1ms| 3ms | 2ms | 168.032
| |  P99| 14ms| 77ms | 63ms | 438.880
| PluginStore.SetWithOptions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.035
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 22ms | 8ms | 56.339
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 1ms | -1ms | -60.505
| |  P99| 21ms| 15ms | -6ms | -28.090
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 0s | -1ms | -163.900
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPersistentNotificationStore.Get |  Avg| 1ms| 0s | -1ms | -121.350
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 9ms | -5ms | -34.694
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.380
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 18ms | -5ms | -21.871
| PostStore.AnalyticsPostCount |  Avg| 225ms| 13ms | -212ms | -94.170
| |  P99| 495ms| 25ms | -470ms | -94.949
| PostStore.Delete |  Avg| 10ms| 9ms | -1ms | -9.964
| |  P99| 25ms| 24ms | -1ms | -4.063
| PostStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 27ms | -3ms | -9.976
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.146
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.406
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 4ms | 1ms | 29.389
| |  P99| 43ms| 45ms | 2ms | 4.624
| PostStore.GetPostReminders |  Avg| 3ms| 5ms | 2ms | 57.236
| |  P99| 9ms| 22ms | 13ms | 142.077
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 30ms | 2ms | 7.160
| PostStore.GetPostsAfter |  Avg| 2ms| 4ms | 2ms | 85.592
| |  P99| 7ms| 69ms | 62ms | 898.483
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.238
| PostStore.GetPostsSince |  Avg| 11ms| 10ms | -1ms | -9.379
| |  P99| 74ms| 74ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -9.899
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.089
| PostStore.SearchPostsForUser |  Avg| 157ms| 154ms | -3ms | -1.906
| |  P99| 2.312s| 2.307s | -5ms | -0.216
| PostStore.SetPostReminder |  Avg| 4ms| 6ms | 2ms | 54.681
| |  P99| 9ms| 48ms | 39ms | 419.168
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 39ms| 25ms | -14ms | -35.897
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 7ms | 3ms | 70.263
| |  P99| 45ms| 95ms | 50ms | 109.894
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 30ms | 5ms | 20.071
| PreferenceStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 56ms| 57ms | 1ms | 1.790
| ProductNoticesStore.ClearOldNotices |  Avg| 26ms| 0s | -26ms | -101.197
| |  P99| 50ms| 0s | -50ms | -100.460
| ProductNoticesStore.GetViews |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.597
| ProductNoticesStore.View |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 217ms| 212ms | -5ms | -2.309
| ReactionStore.ExistsOnPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.361
| ReactionStore.GetForPost |  Avg| 1ms| 2ms | 1ms | 70.381
| |  P99| 16ms| 19ms | 3ms | 18.600
| ReactionStore.GetUniqueCountForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.826
| ReactionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 39ms| 32ms | -7ms | -18.109
| RetentionPolicyStore.GetAll |  Avg| 5ms| 1ms | -4ms | -82.858
| |  P99| 24ms| 5ms | -19ms | -77.869
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -127.922
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 5ms| 4ms | -1ms | -21.117
| |  P99| 44ms| 19ms | -25ms | -56.496
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.168
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 13ms | 4ms | 42.138
| SessionStore.Remove |  Avg| 3ms| 2ms | -1ms | -39.175
| |  P99| 9ms| 5ms | -4ms | -43.478
| SessionStore.Save |  Avg| 5ms| 6ms | 1ms | 18.268
| |  P99| 40ms| 40ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.246
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.332
| StatusStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.718
| StatusStore.SaveOrUpdate |  Avg| 39ms| 55ms | 16ms | 40.613
| |  P99| 659ms| 496ms | -163ms | -24.744
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.929
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 3ms | 1ms | 40.753
| |  P99| 16ms| 17ms | 1ms | 6.420
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.943
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -8.764
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.201
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 9ms | -4ms | -31.374
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.267
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.189
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.297
| TeamStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 91ms| 90ms | -1ms | -1.105
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.094
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.900
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 24ms | -4ms | -14.064
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.189
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 28ms| 25ms | -3ms | -10.544
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.265
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.199
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 9ms | -4ms | -31.055
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.329
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 23ms| 27ms | 4ms | 17.644
| |  P99| 49ms| 50ms | 1ms | 2.041
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 49ms| 48ms | -1ms | -2.048
| |  P99| 325ms| 313ms | -12ms | -3.695
| UserStore.Count |  Avg| 15ms| 16ms | 1ms | 6.850
| |  P99| 76ms| 47ms | -29ms | -38.153
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 22.088
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 251ms| 251ms | 0s | 0.000
| |  P99| 907ms| 907ms | 0s | 0.000
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.226
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 23ms | 14ms | 147.370
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 168ms| 167ms | -1ms | -0.595
| |  P99| 395ms| 405ms | 10ms | 2.530
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.358
| UserStore.Save |  Avg| 70ms| 70ms | 0s | 0.000
| |  P99| 211ms| 211ms | 0s | 0.000
| UserStore.Search |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 43ms| 38ms | -5ms | -11.541
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.180
| UserStore.UpdateLastLogin |  Avg| 4ms| 5ms | 1ms | 22.660
| |  P99| 22ms| 22ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 5ms | 1ms | 22.512
| |  P99| 22ms| 23ms | 1ms | 4.537
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.393
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 32ms | 2ms | 6.766
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 273ms| 263ms | -10ms | -3.669
| | P99| 677ms| 496ms | -181ms | -26.717
| addTeamMember | Avg| 788ms| 791ms | 3ms | 0.381
| | P99| 2.436s| 2.439s | 3ms | 0.123
| autocompleteChannelsForTeamForSearch | Avg| 25ms| 27ms | 2ms | 7.866
| | P99| 210ms| 182ms | -28ms | -13.307
| autocompleteUsers | Avg| 42ms| 41ms | -1ms | -2.408
| | P99| 236ms| 222ms | -14ms | -5.939
| channelMemberCountsByGroup | Avg| 5ms| 0s | -5ms | -101.805
| | P99| 47ms| 0s | -47ms | -99.758
| createChannel | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 334ms| 285ms | -49ms | -14.649
| | P99| 984ms| 911ms | -73ms | -7.419
| createGroupChannel | Avg| 423ms| 425ms | 2ms | 0.473
| | P99| 987ms| 1.27s | 283ms | 28.682
| createPost | Avg| 286ms| 305ms | 19ms | 6.643
| | P99| 1.391s| 1.293s | -98ms | -7.043
| createUser | Avg| 96ms| 97ms | 1ms | 1.037
| | P99| 250ms| 255ms | 5ms | 2.003
| deleteDraft | Avg| 1ms| 3ms | 2ms | 149.040
| | P99| 5ms| 5ms | 0s | 0.000
| deletePost | Avg| 13ms| 14ms | 1ms | 7.496
| | P99| 25ms| 48ms | 23ms | 92.588
| followThreadByUser | Avg| 9ms| 8ms | -1ms | -11.461
| | P99| 24ms| 23ms | -1ms | -4.228
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 28ms| 25ms | -3ms | -10.899
| getAnalytics | Avg| 30ms| 30ms | 0s | 0.000
| | P99| 96ms| 98ms | 2ms | 2.092
| getCategoriesForTeamForUser | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 84ms| 83ms | -1ms | -1.185
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 37ms | 14ms | 61.949
| getChannelMember | Avg| 3ms| 4ms | 1ms | 30.023
| | P99| 29ms| 35ms | 6ms | 20.424
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelMembersForUser | Avg| 15ms| 14ms | -1ms | -6.772
| | P99| 49ms| 49ms | 0s | 0.000
| getChannelStats | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 1ms | -1ms | -61.964
| | P99| 19ms| 5ms | -14ms | -74.268
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.028
| getChannelsForUser | Avg| 10ms| 4ms | -6ms | -60.182
| | P99| 197ms| 72ms | -125ms | -63.533
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 48ms| 53ms | 5ms | 10.500
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 30ms| 28ms | -2ms | -6.690
| | P99| 218ms| 97ms | -121ms | -55.379
| getDrafts | Avg| 4ms| 1ms | -3ms | -84.581
| | P99| 10ms| 5ms | -5ms | -50.743
| getFilePreview | Avg| 42ms| 43ms | 1ms | 2.365
| | P99| 195ms| 205ms | 10ms | 5.130
| getFileThumbnail | Avg| 33ms| 34ms | 1ms | 3.001
| | P99| 98ms| 100ms | 2ms | 2.035
| getFilteredUsersStats | Avg| 15ms| 16ms | 1ms | 6.724
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 1ms| 2ms | 1ms | 92.074
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 62.175
| getLicenseSelfServeStatus | Avg| 61ms| 57ms | -4ms | -6.600
| | P99| 99ms| 99ms | 0s | 0.000
| getOnboarding | Avg| 5ms| 0s | -5ms | -98.995
| | P99| 10ms| 0s | -10ms | -100.503
| getPostThread | Avg| 6ms| 7ms | 1ms | 15.476
| | P99| 60ms| 53ms | -7ms | -11.687
| getPostsForChannel | Avg| 19ms| 17ms | -2ms | -10.725
| | P99| 193ms| 174ms | -19ms | -9.836
| getPostsForChannelAroundLastUnread | Avg| 22ms| 19ms | -3ms | -13.414
| | P99| 397ms| 291ms | -106ms | -26.706
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 27ms| 32ms | 5ms | 18.323
| getPrevTrialLicense | Avg| 2ms| 1ms | -1ms | -40.263
| | P99| 23ms| 5ms | -18ms | -77.081
| getProductNotices | Avg| 5ms| 4ms | -1ms | -21.018
| | P99| 10ms| 5ms | -5ms | -50.469
| getProfileImage | Avg| 85ms| 63ms | -22ms | -25.736
| | P99| 460ms| 451ms | -9ms | -1.956
| getPublicChannelsForTeam | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 46ms| 46ms | 0s | 0.000
| getRolesByNames | Avg| 2ms| 0s | -2ms | -94.584
| | P99| 44ms| 5ms | -39ms | -87.643
| getSelfHostedProducts | Avg| 18ms| 15ms | -3ms | -16.290
| | P99| 99ms| 49ms | -50ms | -50.761
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.141
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 31ms| 33ms | 2ms | 6.378
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.167
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 43ms| 39ms | -4ms | -9.289
| getThreadForUser | Avg| 10ms| 0s | -10ms | -96.291
| | P99| 25ms| 0s | -25ms | -100.604
| getThreadsForUser | Avg| 4ms| 3ms | -1ms | -27.992
| | P99| 25ms| 24ms | -1ms | -4.038
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 40ms | 1ms | 2.532
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 23ms| 22ms | -1ms | -4.288
| | P99| 243ms| 243ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.270
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -5.068
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 68ms| 69ms | 1ms | 1.465
| | P99| 416ms| 424ms | 8ms | 1.924
| logout | Avg| 46ms| 45ms | -1ms | -2.167
| | P99| 92ms| 98ms | 6ms | 6.519
| patchPost | Avg| 49ms| 77ms | 28ms | 57.443
| | P99| 235ms| 2.335s | 2.1s | 895.509
| removeUserCustomStatus | Avg| 201ms| 188ms | -13ms | -6.453
| | P99| 605ms| 489ms | -116ms | -19.172
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 104ms| 99ms | -5ms | -4.821
| searchAllChannels | Avg| 46ms| 47ms | 1ms | 2.160
| | P99| 181ms| 100ms | -81ms | -44.865
| searchGroupChannels | Avg| 3ms| 4ms | 1ms | 29.281
| | P99| 25ms| 30ms | 5ms | 20.353
| searchPostsInTeam | Avg| 164ms| 159ms | -5ms | -3.042
| | P99| 2.333s| 2.319s | -14ms | -0.600
| searchUsers | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| setPostReminder | Avg| 16ms| 19ms | 3ms | 18.427
| | P99| 93ms| 95ms | 2ms | 2.151
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 69ms| 46ms | -23ms | -33.575
| updateCategoriesForTeamForUser | Avg| 46ms| 51ms | 5ms | 10.912
| | P99| 227ms| 220ms | -7ms | -3.087
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 36ms| 24ms | -12ms | -33.614
| updateReadStateThreadByUser | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 141ms| 129ms | -12ms | -8.488
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 409ms| 427ms | 18ms | 4.400
| | P99| 993ms| 992ms | -1ms | -0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 54ms| 53ms | -1ms | -1.846
