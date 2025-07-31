### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 2ms | 527ms | 525ms | 29607.06
| PostStore.SearchPostsForUser | avg | 77ms | 98ms | 21ms | 27.25
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | p99 | 5ms | 995ms | 990ms | 19986.64
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 22ms | 17ms | 343.43
| ThreadStore.MarkAllAsReadByChannels | p99 | 5ms | 19ms | 14ms | 282.83
| ChannelStore.GetChannelUnread | p99 | 5ms | 19ms | 14ms | 282.83
| LinkMetadataStore.Save | p99 | 5ms | 19ms | 14ms | 282.83
| FileInfoStore.GetByIds | p99 | 9ms | 19ms | 10ms | 112.15
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 5ms | 10ms | 5ms | 101.01
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| PostStore.GetPostsAfter | p99 | 5ms | 9ms | 4ms | 80.81
| UserStore.GetMany | p99 | 5ms | 9ms | 4ms | 80.81
| DraftStore.Delete | p99 | 10ms | 16ms | 6ms | 60.82
| StatusStore.UpdateExpiredDNDStatuses | p99 | 18ms | 28ms | 10ms | 54.57
| ChannelStore.SearchGroupChannels | p99 | 24ms | 30ms | 6ms | 25.52
| JobStore.GetNewestJobByStatusesAndType | p99 | 17ms | 20ms | 3ms | 17.29
| ChannelStore.GetFileCount | p99 | 21ms | 24ms | 3ms | 14.34
| JobStore.GetCountByStatusAndType | p99 | 16ms | 18ms | 2ms | 12.16
| JobStore.Save | p99 | 19ms | 21ms | 2ms | 10.70
| UserStore.Search | p99 | 72ms | 76ms | 4ms | 5.52
| PostStore.SearchPostsForUser | p99 | 923ms | 944ms | 21ms | 2.28
| ProductNoticesStore.View | p99 | 245ms | 248ms | 3ms | 1.23
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -120.75
| JobStore.GetAllByTypePage | avg | 2ms | 0s | -2ms | -118.01
| UserStore.GetProfileByGroupChannelIdsForUser | avg | 4ms | 0s | -4ms | -107.84
| PluginStore.Delete | avg | 4ms | 0s | -4ms | -106.99
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -96.18
| PluginStore.SetWithOptions | avg | 8ms | 0s | -8ms | -94.24
| UserStore.GetProfilesInChannel | avg | 28ms | 11ms | -17ms | -60.99
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 20ms | 9ms | -11ms | -55.44
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 2ms | -2ms | -46.36
| ChannelBookmarkStore.Delete | avg | 7ms | 4ms | -3ms | -42.78
| ScheduledPostStore.CreateScheduledPost | avg | 5ms | 3ms | -2ms | -42.59
| ChannelStore.CreateInitialSidebarCategories | avg | 30ms | 22ms | -8ms | -26.44
| UserStore.Update | avg | 9ms | 7ms | -2ms | -23.17
| ChannelStore.CreateDirectChannel | avg | 24ms | 20ms | -4ms | -16.59
| ChannelStore.UpdateSidebarCategories | avg | 38ms | 32ms | -6ms | -15.96
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 15ms | 13ms | -2ms | -13.38
| ChannelStore.AutocompleteInTeamForSearch | avg | 30ms | 27ms | -3ms | -9.90
| ChannelStore.SaveMember | avg | 39ms | 37ms | -2ms | -5.19
| ProductNoticesStore.View | avg | 44ms | 42ms | -2ms | -4.56
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Delete | p99 | 37ms | 0s | -37ms | -101.14
| JobStore.GetAllByTypePage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| UserStore.GetProfileByGroupChannelIdsForUser | p99 | 5ms | 0s | -5ms | -100.89
| PluginStore.SetWithOptions | p99 | 74ms | 0s | -74ms | -99.98
| PostPersistentNotificationStore.DeleteExpired | p99 | 86ms | 5ms | -81ms | -93.65
| UserStore.GetProfilesInChannel | p99 | 241ms | 25ms | -216ms | -89.63
| JobStore.UpdateStatus | p99 | 79ms | 9ms | -70ms | -88.62
| ScheduledPostStore.CreateScheduledPost | p99 | 24ms | 5ms | -19ms | -80.34
| JobStore.UpdateStatusOptimistically | p99 | 39ms | 8ms | -31ms | -78.49
| PostPersistentNotificationStore.Get | p99 | 21ms | 5ms | -16ms | -76.38
| ChannelStore.CreateDirectChannel | p99 | 169ms | 49ms | -120ms | -70.80
| ChannelStore.GetPinnedPostCount | p99 | 13ms | 5ms | -8ms | -61.46
| UserStore.Update | p99 | 84ms | 36ms | -48ms | -57.31
| PostStore.GetPostReminders | p99 | 46ms | 22ms | -24ms | -52.46
| ReactionStore.GetForPost | p99 | 18ms | 9ms | -9ms | -51.38
| ChannelBookmarkStore.Delete | p99 | 10ms | 5ms | -5ms | -50.24
| FileInfoStore.SetContent | p99 | 46ms | 23ms | -23ms | -50.21
| ClusterDiscoveryStore.SetLastPingAt | p99 | 40ms | 20ms | -20ms | -49.69
| PostStore.Update | p99 | 49ms | 25ms | -24ms | -48.73
| ChannelStore.Save | p99 | 122ms | 63ms | -59ms | -48.17
| FileInfoStore.AttachToPost | p99 | 51ms | 27ms | -24ms | -47.12
| UserStore.GetByUsername | p99 | 19ms | 10ms | -9ms | -47.00
| JobStore.UpdateOptimistically | p99 | 39ms | 21ms | -18ms | -46.46
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -43.01
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 154ms | 88ms | -66ms | -42.86
| FileInfoStore.Get | p99 | 8ms | 5ms | -3ms | -38.11
| RoleStore.GetByNames | p99 | 8ms | 5ms | -3ms | -37.97
| JobStore.GetAllByStatus | p99 | 37ms | 24ms | -13ms | -35.20
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 118ms | 80ms | -38ms | -32.11
| UserStore.GetUnreadCount | p99 | 15ms | 11ms | -4ms | -26.80
| PostAcknowledgementStore.GetForPost | p99 | 23ms | 17ms | -6ms | -25.92
| PropertyValueStore.SearchPropertyValues | p99 | 30ms | 23ms | -7ms | -23.70
| ChannelStore.GetPublicChannelsForTeam | p99 | 45ms | 35ms | -10ms | -22.46
| ThreadStore.GetThreadForUser | p99 | 32ms | 25ms | -7ms | -22.08
| ChannelStore.CreateInitialSidebarCategories | p99 | 223ms | 176ms | -47ms | -21.08
| ThreadStore.MaintainMembership | p99 | 37ms | 30ms | -7ms | -18.71
| DraftStore.Get | p99 | 11ms | 9ms | -2ms | -18.28
| StatusStore.UpdateLastActivityAt | p99 | 18ms | 15ms | -3ms | -16.99
| ChannelStore.GetByName | p99 | 59ms | 50ms | -9ms | -15.25
| DraftStore.GetDraftsForUser | p99 | 22ms | 19ms | -3ms | -13.82
| StatusStore.SaveOrUpdate | p99 | 30ms | 26ms | -4ms | -13.27
| PreferenceStore.Save | p99 | 114ms | 99ms | -15ms | -13.14
| PostPriorityStore.GetForPost | p99 | 23ms | 20ms | -3ms | -12.81
| ChannelStore.GetChannels | p99 | 32ms | 28ms | -4ms | -12.41
| ChannelStore.IncrementMentionCount | p99 | 37ms | 33ms | -4ms | -10.88
| UserStore.GetAllProfiles | p99 | 38ms | 34ms | -4ms | -10.61
| ChannelStore.Get | p99 | 39ms | 35ms | -4ms | -10.35
| ThreadStore.GetMembershipForUser | p99 | 19ms | 17ms | -2ms | -10.30
| ThreadStore.GetThreadFollowers | p99 | 20ms | 18ms | -2ms | -10.03
| TeamStore.GetMember | p99 | 41ms | 37ms | -4ms | -9.64
| ChannelStore.GetMembersForUser | p99 | 32ms | 29ms | -3ms | -9.47
| UserStore.Count | p99 | 75ms | 68ms | -7ms | -9.35
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 22ms | 20ms | -2ms | -9.28
| ThreadStore.GetTeamsUnreadForUser | p99 | 54ms | 49ms | -5ms | -9.19
| ChannelStore.IsReadOnlyChannel | p99 | 23ms | 21ms | -2ms | -8.79
| GroupStore.GetByName | p99 | 48ms | 44ms | -4ms | -8.26
| UserStore.UpdateFailedPasswordAttempts | p99 | 51ms | 47ms | -4ms | -7.92
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 39ms | 36ms | -3ms | -7.73
| UserStore.GetProfileByIds | p99 | 39ms | 36ms | -3ms | -7.65
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 46ms | 43ms | -3ms | -6.47
| WebhookStore.GetOutgoingByTeam | p99 | 37ms | 35ms | -2ms | -5.35
| ThreadStore.GetTotalUnreadMentions | p99 | 38ms | 36ms | -2ms | -5.31
| PostStore.GetEtag | p99 | 38ms | 36ms | -2ms | -5.24
| UserStore.AutocompleteUsersInChannel | p99 | 192ms | 182ms | -10ms | -5.20
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 40ms | 38ms | -2ms | -4.98
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 42ms | 40ms | -2ms | -4.78
| PostStore.Save | p99 | 84ms | 80ms | -4ms | -4.76
| StatusStore.Get | p99 | 42ms | 40ms | -2ms | -4.72
| UserStore.UpdateLastLogin | p99 | 43ms | 41ms | -2ms | -4.62
| ChannelStore.GetMember | p99 | 45ms | 43ms | -2ms | -4.47
| ChannelStore.GetMemberLastViewedAt | p99 | 45ms | 43ms | -2ms | -4.43
| SystemStore.GetByName | p99 | 45ms | 43ms | -2ms | -4.43
| SessionStore.GetLRUSessions | p99 | 45ms | 43ms | -2ms | -4.40
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 46ms | 44ms | -2ms | -4.39
| TeamStore.GetAllPage | p99 | 47ms | 45ms | -2ms | -4.29
| TeamStore.GetTeamsForUser | p99 | 47ms | 45ms | -2ms | -4.28
| SessionStore.Get | p99 | 86ms | 84ms | -2ms | -2.32
| ChannelStore.SaveMember | p99 | 227ms | 224ms | -3ms | -1.32
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | avg | 84ms | 106ms | 22ms | 26.32
| logout | avg | 25ms | 30ms | 5ms | 20.23
| setPostReminder | avg | 16ms | 18ms | 2ms | 12.85
| createDirectChannel | avg | 191ms | 196ms | 5ms | 2.61
| uploadFileStream | avg | 458ms | 468ms | 10ms | 2.19
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelUnread | p99 | 5ms | 19ms | 14ms | 282.83
| logout | p99 | 49ms | 93ms | 44ms | 90.10
| unfollowThreadByUser | p99 | 25ms | 38ms | 13ms | 52.33
| getFilePreview | p99 | 105ms | 150ms | 45ms | 42.66
| searchGroupChannels | p99 | 24ms | 30ms | 6ms | 25.52
| uploadFileStream | p99 | 1.633s | 2.009s | 376ms | 23.03
| login | p99 | 563ms | 638ms | 75ms | 13.33
| patchPost | p99 | 98ms | 103ms | 5ms | 5.08
| getPostThread | p99 | 43ms | 45ms | 2ms | 4.68
| searchUsers | p99 | 76ms | 79ms | 3ms | 3.97
| getFileThumbnail | p99 | 97ms | 100ms | 3ms | 3.08
| searchPostsInTeam | p99 | 927ms | 949ms | 22ms | 2.37
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getRolesByNames | avg | 5ms | 0s | -5ms | -108.13
| getJobsByType | avg | 2ms | 0s | -2ms | -104.34
| deleteChannelBookmark | avg | 17ms | 0s | -17ms | -101.00
| getAnalytics | avg | 44ms | 0s | -44ms | -99.31
| getChannelMembers | avg | 3ms | 0s | -3ms | -88.27
| getCategoriesForTeamForUser | avg | 21ms | 9ms | -12ms | -57.81
| createChannel | avg | 210ms | 160ms | -50ms | -23.84
| getProfileImage | avg | 100ms | 87ms | -13ms | -12.95
| createChannelBookmark | avg | 19ms | 17ms | -2ms | -10.34
| autocompleteChannelsForTeamForSearch | avg | 30ms | 27ms | -3ms | -9.88
| updateCategoriesForTeamForUser | avg | 54ms | 49ms | -5ms | -9.26
| createUser | avg | 179ms | 173ms | -6ms | -3.36
| createGroupChannel | avg | 298ms | 289ms | -9ms | -3.02
| addTeamMember | avg | 835ms | 811ms | -24ms | -2.87
| addChannelMember | avg | 196ms | 192ms | -4ms | -2.04
| createPost | avg | 179ms | 176ms | -3ms | -1.68
| removeUserCustomStatus | avg | 126ms | 124ms | -2ms | -1.59
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| getPrevTrialLicense | p99 | 5ms | 0s | -5ms | -101.01
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| getAnalytics | p99 | 50ms | 0s | -50ms | -100.44
| getJobsByType | p99 | 8ms | 0s | -8ms | -100.00
| createSchedulePost | p99 | 45ms | 9ms | -36ms | -79.12
| getFilteredUsersStats | p99 | 25ms | 10ms | -15ms | -60.73
| getRolesByNames | p99 | 10ms | 5ms | -5ms | -50.51
| createChannel | p99 | 487ms | 249ms | -238ms | -48.82
| createChannelBookmark | p99 | 48ms | 25ms | -23ms | -47.67
| getCategoriesForTeamForUser | p99 | 141ms | 86ms | -55ms | -39.03
| updatePreferences | p99 | 35ms | 23ms | -12ms | -34.29
| listCPAValues | p99 | 30ms | 23ms | -7ms | -23.70
| deleteDraft | p99 | 13ms | 10ms | -3ms | -23.12
| getPublicChannelsForTeam | p99 | 45ms | 35ms | -10ms | -22.46
| getProfileImage | p99 | 583ms | 466ms | -117ms | -20.08
| createGroupChannel | p99 | 610ms | 497ms | -113ms | -18.53
| getDrafts | p99 | 22ms | 19ms | -3ms | -13.37
| getChannelsForTeamForUser | p99 | 33ms | 29ms | -4ms | -11.94
| getChannelMembersForTeamForUser | p99 | 33ms | 30ms | -3ms | -9.05
| listChannelBookmarksForChannel | p99 | 24ms | 22ms | -2ms | -8.50
| getChannel | p99 | 37ms | 34ms | -3ms | -8.05
| createUser | p99 | 662ms | 618ms | -44ms | -6.64
| autocompleteUsers | p99 | 173ms | 162ms | -11ms | -6.36
| getUsers | p99 | 84ms | 79ms | -5ms | -5.93
| getTeamScheduledPosts | p99 | 88ms | 83ms | -5ms | -5.68
| viewChannel | p99 | 90ms | 86ms | -4ms | -4.45
| getTeamsForUser | p99 | 48ms | 46ms | -2ms | -4.20
| getChannelsForUser | p99 | 48ms | 46ms | -2ms | -4.19
| getTeamMembersForUser | p99 | 50ms | 48ms | -2ms | -4.01
| getAllTeams | p99 | 51ms | 49ms | -2ms | -3.91
| getUser | p99 | 85ms | 82ms | -3ms | -3.54
| getTeamsUnreadForUser | p99 | 87ms | 84ms | -3ms | -3.45
| getClientConfig | p99 | 99ms | 96ms | -3ms | -3.04
| getChannelMember | p99 | 94ms | 92ms | -2ms | -2.12
| updateReadStateThreadByUser | p99 | 97ms | 95ms | -2ms | -2.06
| createPost | p99 | 927ms | 910ms | -17ms | -1.83
| createDirectChannel | p99 | 494ms | 485ms | -9ms | -1.82
| getPostsForChannelAroundLastUnread | p99 | 221ms | 217ms | -4ms | -1.81
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 45ms | -1ms | -2.168
| BotStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.292
| BotStore.GetAll |  Avg| 1ms| 0s | -1ms | -66.965
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 7ms| 4ms | -3ms | -42.779
| |  P99| 10ms| 5ms | -5ms | -50.235
| ChannelBookmarkStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.281
| ChannelBookmarkStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.098
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.733
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 30ms| 27ms | -3ms | -9.905
| |  P99| 89ms| 90ms | 1ms | 1.125
| ChannelStore.CreateDirectChannel |  Avg| 24ms| 20ms | -4ms | -16.589
| |  P99| 169ms| 49ms | -120ms | -70.798
| ChannelStore.CreateInitialSidebarCategories |  Avg| 30ms| 22ms | -8ms | -26.442
| |  P99| 223ms| 176ms | -47ms | -21.085
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 35ms | -4ms | -10.351
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.625
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 15ms| 13ms | -2ms | -13.384
| |  P99| 154ms| 88ms | -66ms | -42.857
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 59ms| 50ms | -9ms | -15.253
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.828
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 28ms | -4ms | -12.413
| ChannelStore.GetChannelsByUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.118
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.888
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.338
| ChannelStore.GetGuestCount |  Avg| 6ms| 5ms | -1ms | -17.967
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 5ms| 4ms | -1ms | -21.763
| |  P99| 45ms| 43ms | -2ms | -4.471
| ChannelStore.GetMemberCount |  Avg| 19ms| 18ms | -1ms | -5.342
| |  P99| 85ms| 84ms | -1ms | -1.172
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.433
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -96.177
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 4ms| 3ms | -1ms | -28.112
| |  P99| 32ms| 29ms | -3ms | -9.467
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| ChannelStore.GetMembersForUserWithPagination |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.090
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -61.458
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 13ms | -1ms | -7.332
| |  P99| 45ms| 35ms | -10ms | -22.458
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 20ms| 9ms | -11ms | -55.441
| |  P99| 118ms| 80ms | -38ms | -32.107
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 33ms | -4ms | -10.882
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.791
| ChannelStore.Save |  Avg| 12ms| 11ms | -1ms | -8.004
| |  P99| 122ms| 63ms | -59ms | -48.166
| ChannelStore.SaveMember |  Avg| 39ms| 37ms | -2ms | -5.189
| |  P99| 227ms| 224ms | -3ms | -1.323
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 29.152
| |  P99| 24ms| 30ms | 6ms | 25.520
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.783
| ChannelStore.UpdateSidebarCategories |  Avg| 38ms| 32ms | -6ms | -15.958
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 20ms | -20ms | -49.691
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 16ms | 6ms | 60.817
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 3ms | -1ms | -24.648
| |  P99| 10ms| 9ms | -1ms | -10.363
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 9ms | -2ms | -18.283
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 19ms | -3ms | -13.819
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -14.147
| |  P99| 51ms| 27ms | -24ms | -47.124
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.111
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 19ms | 10ms | 112.150
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 7ms | -1ms | -12.295
| |  P99| 46ms| 23ms | -23ms | -50.205
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 4ms| 3ms | -1ms | -27.253
| |  P99| 40ms| 38ms | -2ms | -4.982
| GroupStore.GetByName |  Avg| 5ms| 4ms | -1ms | -21.444
| |  P99| 48ms| 44ms | -4ms | -8.263
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.020
| JobStore.GetAllByStatus |  Avg| 3ms| 2ms | -1ms | -34.555
| |  P99| 37ms| 24ms | -13ms | -35.197
| JobStore.GetAllByTypePage |  Avg| 2ms| 0s | -2ms | -118.011
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.158
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.291
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.695
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 21ms | -18ms | -46.460
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -23.435
| |  P99| 79ms| 9ms | -70ms | -88.621
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -21.696
| |  P99| 39ms| 8ms | -31ms | -78.493
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 31.520
| |  P99| 5ms| 19ms | 14ms | 282.828
| PluginStore.Delete |  Avg| 4ms| 0s | -4ms | -106.988
| |  P99| 37ms| 0s | -37ms | -101.145
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -68.061
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 41ms| 41ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 8ms| 0s | -8ms | -94.245
| |  P99| 74ms| 0s | -74ms | -99.977
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 17ms | -6ms | -25.918
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.181
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 2ms | -2ms | -46.363
| |  P99| 86ms| 5ms | -81ms | -93.650
| PostPersistentNotificationStore.Get |  Avg| 3ms| 2ms | -1ms | -35.301
| |  P99| 21ms| 5ms | -16ms | -76.381
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.351
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 20ms | -3ms | -12.813
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 24ms | -1ms | -4.013
| PostStore.AnalyticsPostCount |  Avg| 2ms| 527ms | 525ms | 29607.055
| |  P99| 5ms| 995ms | 990ms | 19986.640
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 35ms| 34ms | -1ms | -2.840
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 38ms| 36ms | -2ms | -5.243
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 37ms | -1ms | -2.598
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 8ms| 7ms | -1ms | -12.910
| |  P99| 46ms| 22ms | -24ms | -52.459
| PostStore.GetPosts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 42ms | -1ms | -2.313
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.055
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.854
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 84ms| 80ms | -4ms | -4.758
| PostStore.SearchPostsForUser |  Avg| 77ms| 98ms | 21ms | 27.253
| |  P99| 923ms| 944ms | 21ms | 2.275
| PostStore.SetPostReminder |  Avg| 6ms| 7ms | 1ms | 16.232
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 12ms | -1ms | -7.889
| |  P99| 49ms| 25ms | -24ms | -48.730
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.557
| PreferenceStore.GetAll |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 114ms| 99ms | -15ms | -13.139
| ProductNoticesStore.View |  Avg| 44ms| 42ms | -2ms | -4.565
| |  P99| 245ms| 248ms | 3ms | 1.226
| PropertyFieldStore.SearchPropertyFields |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.217
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 30ms| 23ms | -7ms | -23.705
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -51.380
| RetentionPolicyStore.GetAll |  Avg| 1ms| 0s | -1ms | -73.091
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -153.681
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.975
| ScheduledPostStore.CreateScheduledPost |  Avg| 5ms| 3ms | -2ms | -42.586
| |  P99| 24ms| 5ms | -19ms | -80.338
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 46ms| 43ms | -3ms | -6.467
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 22ms | 17ms | 343.434
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -120.746
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 84ms | -2ms | -2.319
| SessionStore.GetLRUSessions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.405
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.011
| SessionStore.Save |  Avg| 10ms| 9ms | -1ms | -10.450
| |  P99| 77ms| 76ms | -1ms | -1.305
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.084
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.896
| StatusStore.Get |  Avg| 4ms| 3ms | -1ms | -26.828
| |  P99| 42ms| 40ms | -2ms | -4.720
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.720
| StatusStore.SaveOrUpdate |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 30ms| 26ms | -4ms | -13.269
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 3ms | 1ms | 41.993
| |  P99| 18ms| 28ms | 10ms | 54.570
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 15ms | -3ms | -16.993
| SystemStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 43ms | -2ms | -4.432
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.685
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 47ms| 45ms | -2ms | -4.286
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 4ms | -1ms | -22.204
| |  P99| 46ms| 44ms | -2ms | -4.386
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 37ms | -4ms | -9.639
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 4ms | -1ms | -21.331
| |  P99| 47ms| 46ms | -1ms | -2.119
| TeamStore.GetTeamsForUser |  Avg| 5ms| 4ms | -1ms | -21.658
| |  P99| 47ms| 45ms | -2ms | -4.282
| TeamStore.GetTotalMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 30ms| 29ms | -1ms | -3.373
| |  P99| 172ms| 172ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.300
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 54ms| 49ms | -5ms | -9.190
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.033
| ThreadStore.GetThreadForUser |  Avg| 6ms| 5ms | -1ms | -17.973
| |  P99| 32ms| 25ms | -7ms | -22.077
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.110
| ThreadStore.GetTotalThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 40ms | -1ms | -2.436
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 3ms | -1ms | -28.198
| |  P99| 38ms| 36ms | -2ms | -5.314
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 40ms | -1ms | -2.429
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 40ms | -2ms | -4.775
| ThreadStore.MaintainMembership |  Avg| 7ms| 6ms | -1ms | -15.350
| |  P99| 37ms| 30ms | -7ms | -18.707
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 41.953
| |  P99| 5ms| 19ms | 14ms | 282.828
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.987
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 2ms | 1ms | 66.736
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 39ms| 38ms | -1ms | -2.582
| |  P99| 192ms| 182ms | -10ms | -5.205
| UserStore.Count |  Avg| 15ms| 14ms | -1ms | -6.869
| |  P99| 75ms| 68ms | -7ms | -9.348
| UserStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 34ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 34ms | -4ms | -10.605
| UserStore.GetAllProfilesInChannel |  Avg| 185ms| 185ms | 0s | 0.000
| |  P99| 540ms| 538ms | -2ms | -0.371
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 10ms | -9ms | -46.997
| UserStore.GetForLogin |  Avg| 5ms| 4ms | -1ms | -21.648
| |  P99| 45ms| 45ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 0s | -4ms | -107.843
| |  P99| 5ms| 0s | -5ms | -100.894
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 36ms | -3ms | -7.646
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 2ms | -1ms | -39.730
| |  P99| 20ms| 19ms | -1ms | -4.995
| UserStore.GetProfilesInChannel |  Avg| 28ms| 11ms | -17ms | -60.994
| |  P99| 241ms| 25ms | -216ms | -89.629
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 2ms | -1ms | -39.543
| |  P99| 15ms| 11ms | -4ms | -26.796
| UserStore.IsEmpty |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.Save |  Avg| 84ms| 84ms | 0s | 0.000
| |  P99| 243ms| 242ms | -1ms | -0.411
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 72ms| 76ms | 4ms | 5.523
| UserStore.Update |  Avg| 9ms| 7ms | -2ms | -23.168
| |  P99| 84ms| 36ms | -48ms | -57.314
| UserStore.UpdateFailedPasswordAttempts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 51ms| 47ms | -4ms | -7.920
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 43ms| 41ms | -2ms | -4.625
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 40ms | -1ms | -2.417
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.234
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 4ms | -1ms | -21.808
| |  P99| 37ms| 35ms | -2ms | -5.348
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 196ms| 192ms | -4ms | -2.045
| | P99| 480ms| 478ms | -2ms | -0.416
| addTeamMember | Avg| 835ms| 811ms | -24ms | -2.875
| | P99| 2.456s| 2.46s | 4ms | 0.163
| autocompleteChannelsForTeamForSearch | Avg| 30ms| 27ms | -3ms | -9.882
| | P99| 89ms| 90ms | 1ms | 1.125
| autocompleteUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 173ms| 162ms | -11ms | -6.358
| createChannel | Avg| 210ms| 160ms | -50ms | -23.840
| | P99| 487ms| 249ms | -238ms | -48.822
| createChannelBookmark | Avg| 19ms| 17ms | -2ms | -10.335
| | P99| 48ms| 25ms | -23ms | -47.668
| createDirectChannel | Avg| 191ms| 196ms | 5ms | 2.613
| | P99| 494ms| 485ms | -9ms | -1.822
| createGroupChannel | Avg| 298ms| 289ms | -9ms | -3.020
| | P99| 610ms| 497ms | -113ms | -18.525
| createPost | Avg| 179ms| 176ms | -3ms | -1.678
| | P99| 927ms| 910ms | -17ms | -1.833
| createSchedulePost | Avg| 5ms| 4ms | -1ms | -19.464
| | P99| 45ms| 9ms | -36ms | -79.121
| createUser | Avg| 179ms| 173ms | -6ms | -3.358
| | P99| 662ms| 618ms | -44ms | -6.642
| deleteChannelBookmark | Avg| 17ms| 0s | -17ms | -101.004
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -23.125
| deletePost | Avg| 19ms| 20ms | 1ms | 5.188
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 51ms| 49ms | -2ms | -3.909
| getAnalytics | Avg| 44ms| 0s | -44ms | -99.312
| | P99| 50ms| 0s | -50ms | -100.445
| getCategoriesForTeamForUser | Avg| 21ms| 9ms | -12ms | -57.806
| | P99| 141ms| 86ms | -55ms | -39.027
| getChannel | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 37ms| 34ms | -3ms | -8.054
| getChannelMember | Avg| 11ms| 10ms | -1ms | -9.338
| | P99| 94ms| 92ms | -2ms | -2.118
| getChannelMembers | Avg| 3ms| 0s | -3ms | -88.266
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 33ms| 30ms | -3ms | -9.052
| getChannelMembersForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 48ms| 47ms | -1ms | -2.073
| getChannelStats | Avg| 3ms| 2ms | -1ms | -39.424
| | P99| 49ms| 48ms | -1ms | -2.041
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 19ms | 14ms | 282.828
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 33ms| 29ms | -4ms | -11.943
| getChannelsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 48ms| 46ms | -2ms | -4.187
| getClientConfig | Avg| 12ms| 11ms | -1ms | -8.347
| | P99| 99ms| 96ms | -3ms | -3.044
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 19ms | -3ms | -13.374
| getFilePreview | Avg| 41ms| 42ms | 1ms | 2.453
| | P99| 105ms| 150ms | 45ms | 42.661
| getFileThumbnail | Avg| 35ms| 36ms | 1ms | 2.897
| | P99| 97ms| 100ms | 3ms | 3.079
| getFilteredUsersStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 10ms | -15ms | -60.729
| getJobsByType | Avg| 2ms| 0s | -2ms | -104.340
| | P99| 8ms| 0s | -8ms | -100.004
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 43ms| 45ms | 2ms | 4.681
| getPostsForChannel | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 198ms| 197ms | -1ms | -0.504
| getPostsForChannelAroundLastUnread | Avg| 27ms| 26ms | -1ms | -3.698
| | P99| 221ms| 217ms | -4ms | -1.814
| getPreferences | Avg| 6ms| 5ms | -1ms | -17.946
| | P99| 49ms| 49ms | 0s | 0.000
| getPrevTrialLicense | Avg| 1ms| 0s | -1ms | -95.792
| | P99| 5ms| 0s | -5ms | -101.010
| getProfileImage | Avg| 100ms| 87ms | -13ms | -12.947
| | P99| 583ms| 466ms | -117ms | -20.076
| getPublicChannelsForTeam | Avg| 15ms| 14ms | -1ms | -6.879
| | P99| 45ms| 35ms | -10ms | -22.458
| getRolesByNames | Avg| 5ms| 0s | -5ms | -108.135
| | P99| 10ms| 5ms | -5ms | -50.505
| getTeamMember | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 18ms | 1ms | 5.737
| getTeamMembersForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 50ms| 48ms | -2ms | -4.012
| getTeamScheduledPosts | Avg| 9ms| 8ms | -1ms | -10.907
| | P99| 88ms| 83ms | -5ms | -5.683
| getTeamStats | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 5ms| 4ms | -1ms | -20.771
| | P99| 48ms| 46ms | -2ms | -4.203
| getTeamsUnreadForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 87ms| 84ms | -3ms | -3.448
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 47ms| 46ms | -1ms | -2.133
| getUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 85ms| 82ms | -3ms | -3.539
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 7ms| 6ms | -1ms | -14.930
| | P99| 84ms| 79ms | -5ms | -5.934
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -4.916
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 48ms| 49ms | 1ms | 2.071
| listCPAValues | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 30ms| 23ms | -7ms | -23.705
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 22ms | -2ms | -8.502
| login | Avg| 95ms| 94ms | -1ms | -1.052
| | P99| 563ms| 638ms | 75ms | 13.326
| logout | Avg| 25ms| 30ms | 5ms | 20.231
| | P99| 49ms| 93ms | 44ms | 90.100
| patchPost | Avg| 25ms| 24ms | -1ms | -4.020
| | P99| 98ms| 103ms | 5ms | 5.076
| removeUserCustomStatus | Avg| 126ms| 124ms | -2ms | -1.586
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 66ms| 65ms | -1ms | -1.525
| searchAllChannels | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 4ms | 1ms | 28.588
| | P99| 24ms| 30ms | 6ms | 25.520
| searchPostsInTeam | Avg| 84ms| 106ms | 22ms | 26.316
| | P99| 927ms| 949ms | 22ms | 2.374
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 76ms| 79ms | 3ms | 3.968
| setPostReminder | Avg| 16ms| 18ms | 2ms | 12.854
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 13ms | 1ms | 8.351
| | P99| 25ms| 38ms | 13ms | 52.327
| updateCategoriesForTeamForUser | Avg| 54ms| 49ms | -5ms | -9.259
| | P99| 100ms| 99ms | -1ms | -1.005
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 35ms| 23ms | -12ms | -34.286
| updateReadStateThreadByUser | Avg| 37ms| 36ms | -1ms | -2.730
| | P99| 97ms| 95ms | -2ms | -2.060
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 458ms| 468ms | 10ms | 2.186
| | P99| 1.633s| 2.009s | 376ms | 23.025
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 26ms| 25ms | -1ms | -3.820
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 90ms| 86ms | -4ms | -4.454
