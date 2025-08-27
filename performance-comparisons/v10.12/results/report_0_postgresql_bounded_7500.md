### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserAccessTokenStore.GetByToken | avg | 2ms | 4ms | 2ms | 101.93
| ChannelBookmarkStore.Save | avg | 8ms | 14ms | 6ms | 77.47
| ChannelStore.AutocompleteInTeamForSearch | avg | 16ms | 27ms | 11ms | 69.43
| PreferenceStore.DeleteCategoryAndName | avg | 4ms | 7ms | 3ms | 66.78
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 6ms | 9ms | 3ms | 48.57
| ChannelStore.Save | avg | 13ms | 19ms | 6ms | 47.59
| ChannelStore.GetSidebarCategory | avg | 6ms | 8ms | 2ms | 33.30
| StatusStore.SaveOrUpdateMany | avg | 6ms | 8ms | 2ms | 31.35
| PostStore.Delete | avg | 16ms | 19ms | 3ms | 18.40
| SessionStore.Save | avg | 13ms | 15ms | 2ms | 15.15
| ChannelStore.UpdateSidebarCategories | avg | 37ms | 40ms | 3ms | 8.05
| ChannelStore.CreateDirectChannel | avg | 27ms | 29ms | 2ms | 7.33
| ChannelStore.CreateInitialSidebarCategories | avg | 32ms | 34ms | 2ms | 6.30
| ProductNoticesStore.View | avg | 64ms | 68ms | 4ms | 6.29
| TeamStore.SaveMember | avg | 36ms | 38ms | 2ms | 5.51
| PostStore.AnalyticsPostCount | avg | 264ms | 275ms | 11ms | 4.17
| ChannelStore.SaveMember | avg | 49ms | 51ms | 2ms | 4.12
| PostStore.SearchPostsForUser | avg | 87ms | 90ms | 3ms | 3.45
| UserStore.GetAllProfilesInChannel | avg | 210ms | 216ms | 6ms | 2.86
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetChannelUnread | p99 | 5ms | 41ms | 36ms | 727.27
| UserAccessTokenStore.GetByToken | p99 | 5ms | 23ms | 18ms | 363.53
| UserStore.GetMany | p99 | 5ms | 20ms | 15ms | 303.03
| ChannelStore.Save | p99 | 62ms | 213ms | 151ms | 243.54
| ChannelBookmarkStore.Save | p99 | 10ms | 25ms | 15ms | 150.71
| BotStore.Get | p99 | 10ms | 24ms | 14ms | 146.21
| PostStore.SetPostReminder | p99 | 10ms | 24ms | 14ms | 140.70
| StatusStore.SaveOrUpdateMany | p99 | 25ms | 57ms | 32ms | 128.77
| ThreadStore.MarkAllAsReadByChannels | p99 | 18ms | 41ms | 23ms | 125.00
| PluginStore.List | p99 | 9ms | 20ms | 11ms | 120.88
| UserStore.Update | p99 | 41ms | 85ms | 44ms | 106.67
| PostStore.AnalyticsPostCount | p99 | 498ms | 990ms | 492ms | 98.89
| LinkMetadataStore.Get | p99 | 10ms | 19ms | 9ms | 92.55
| PreferenceStore.DeleteCategoryAndName | p99 | 47ms | 90ms | 43ms | 92.47
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 47ms | 90ms | 43ms | 92.47
| PostStore.Delete | p99 | 25ms | 47ms | 22ms | 88.53
| PostStore.GetSingle | p99 | 9ms | 17ms | 8ms | 85.64
| ChannelStore.SearchGroupChannels | p99 | 25ms | 46ms | 21ms | 85.47
| JobStore.GetAllByTypePage | p99 | 5ms | 9ms | 4ms | 80.81
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 9ms | 4ms | 80.79
| ReactionStore.GetForPost | p99 | 23ms | 38ms | 15ms | 64.62
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 8ms | 3ms | 60.61
| UserStore.GetByUsername | p99 | 24ms | 38ms | 14ms | 58.52
| JobStore.GetAllByStatus | p99 | 28ms | 44ms | 16ms | 57.29
| DraftStore.Delete | p99 | 13ms | 20ms | 7ms | 53.64
| FileInfoStore.Get | p99 | 10ms | 15ms | 5ms | 52.05
| ThreadStore.MarkAsRead | p99 | 11ms | 16ms | 5ms | 44.50
| FileInfoStore.GetByIds | p99 | 25ms | 36ms | 11ms | 44.08
| ChannelStore.GetPinnedPostCount | p99 | 13ms | 18ms | 5ms | 39.60
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 13ms | 18ms | 5ms | 38.94
| PostStore.Save | p99 | 97ms | 132ms | 35ms | 35.94
| AuditStore.Save | p99 | 55ms | 73ms | 18ms | 32.61
| UserStore.UpdateLastLogin | p99 | 48ms | 63ms | 15ms | 30.98
| JobStore.GetCountByStatusAndType | p99 | 16ms | 21ms | 5ms | 30.96
| SessionStore.GetLRUSessions | p99 | 52ms | 68ms | 16ms | 30.81
| TeamStore.GetTeamsForUser | p99 | 52ms | 67ms | 15ms | 29.12
| ChannelStore.GetFileCount | p99 | 25ms | 32ms | 7ms | 28.12
| ChannelStore.AutocompleteInTeamForSearch | p99 | 72ms | 92ms | 20ms | 27.87
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 50ms | 64ms | 14ms | 27.83
| ClusterDiscoveryStore.SetLastPingAt | p99 | 43ms | 55ms | 12ms | 27.59
| UserStore.GetForLogin | p99 | 59ms | 75ms | 16ms | 27.22
| ThreadStore.UpdateMembership | p99 | 12ms | 15ms | 3ms | 26.04
| UserStore.Save | p99 | 249ms | 312ms | 63ms | 25.25
| GroupStore.GetByName | p99 | 50ms | 62ms | 12ms | 24.20
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 25ms | 31ms | 6ms | 23.55
| ChannelStore.GetPublicChannelsForTeam | p99 | 39ms | 47ms | 8ms | 20.52
| SharedChannelStore.HasChannel | p99 | 25ms | 30ms | 5ms | 20.21
| PreferenceStore.GetAll | p99 | 65ms | 78ms | 13ms | 20.09
| PostStore.Get | p99 | 40ms | 48ms | 8ms | 19.82
| PropertyFieldStore.SearchPropertyFields | p99 | 54ms | 64ms | 10ms | 18.60
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 54ms | 63ms | 9ms | 16.66
| ChannelStore.GetGuestCount | p99 | 66ms | 77ms | 11ms | 16.64
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 25ms | 29ms | 4ms | 16.21
| UserStore.GetProfilesByUsernames | p99 | 25ms | 29ms | 4ms | 16.10
| ChannelStore.UpdateLastViewedAt | p99 | 25ms | 29ms | 4ms | 16.09
| ChannelStore.GetMember | p99 | 52ms | 60ms | 8ms | 15.28
| ThreadStore.GetThreadsForUser | p99 | 33ms | 38ms | 5ms | 15.03
| TeamStore.GetAllPage | p99 | 60ms | 69ms | 9ms | 15.01
| TeamStore.Get | p99 | 21ms | 24ms | 3ms | 14.39
| PreferenceStore.Get | p99 | 28ms | 32ms | 4ms | 14.13
| PostStore.GetPostsSince | p99 | 50ms | 57ms | 7ms | 13.92
| PostStore.GetPostIdBeforeTime | p99 | 29ms | 33ms | 4ms | 13.90
| ThreadStore.MaintainMembership | p99 | 50ms | 57ms | 7ms | 13.89
| ChannelStore.SaveMember | p99 | 247ms | 281ms | 34ms | 13.75
| ChannelStore.IsReadOnlyChannel | p99 | 31ms | 35ms | 4ms | 12.82
| UserStore.UpdateUpdateAt | p99 | 47ms | 53ms | 6ms | 12.64
| SystemStore.GetByName | p99 | 61ms | 68ms | 7ms | 11.45
| ChannelStore.GetMemberForPost | p99 | 27ms | 30ms | 3ms | 11.09
| PostPersistentNotificationStore.GetSingle | p99 | 18ms | 20ms | 2ms | 10.85
| ChannelStore.GetMembersForUserWithPagination | p99 | 62ms | 68ms | 6ms | 9.75
| UserStore.IsEmpty | p99 | 31ms | 34ms | 3ms | 9.67
| ChannelStore.UpdateSidebarCategories | p99 | 88ms | 96ms | 8ms | 9.14
| PostStore.GetPostsBefore | p99 | 33ms | 36ms | 3ms | 9.04
| UserStore.Get | p99 | 45ms | 49ms | 4ms | 8.91
| UserStore.GetAllProfiles | p99 | 45ms | 49ms | 4ms | 8.86
| PostAcknowledgementStore.GetForPosts | p99 | 35ms | 38ms | 3ms | 8.47
| StatusStore.Get | p99 | 49ms | 53ms | 4ms | 8.23
| ChannelStore.GetMemberLastViewedAt | p99 | 49ms | 53ms | 4ms | 8.16
| UserTermsOfServiceStore.GetByUser | p99 | 56ms | 60ms | 4ms | 7.16
| ThreadStore.GetTotalUnreadMentions | p99 | 44ms | 47ms | 3ms | 6.77
| PostStore.GetEtag | p99 | 45ms | 48ms | 3ms | 6.62
| ChannelStore.Get | p99 | 46ms | 49ms | 3ms | 6.56
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 46ms | 49ms | 3ms | 6.55
| TeamStore.GetTeamsByUserId | p99 | 61ms | 65ms | 4ms | 6.53
| ProductNoticesStore.View | p99 | 416ms | 443ms | 27ms | 6.49
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 46ms | 49ms | 3ms | 6.47
| UserStore.GetAllProfilesInChannel | p99 | 823ms | 875ms | 52ms | 6.32
| ThreadStore.GetTotalUnreadThreads | p99 | 48ms | 51ms | 3ms | 6.26
| ThreadStore.GetTotalThreads | p99 | 48ms | 51ms | 3ms | 6.24
| DraftStore.Upsert | p99 | 34ms | 36ms | 2ms | 5.82
| GroupStore.GetGroups | p99 | 37ms | 39ms | 2ms | 5.45
| UserStore.AutocompleteUsersInChannel | p99 | 188ms | 198ms | 10ms | 5.32
| SessionStore.Save | p99 | 95ms | 100ms | 5ms | 5.26
| PostPriorityStore.GetForPosts | p99 | 39ms | 41ms | 2ms | 5.11
| ChannelStore.CreateDirectChannel | p99 | 197ms | 207ms | 10ms | 5.08
| ChannelStore.GetChannels | p99 | 41ms | 43ms | 2ms | 4.89
| ChannelStore.GetMembersForUser | p99 | 42ms | 44ms | 2ms | 4.75
| FileInfoStore.Save | p99 | 44ms | 46ms | 2ms | 4.58
| ChannelStore.GetAllChannelMembersForUser | p99 | 45ms | 47ms | 2ms | 4.42
| UserStore.GetProfileByIds | p99 | 46ms | 48ms | 2ms | 4.39
| TeamStore.GetMember | p99 | 47ms | 49ms | 2ms | 4.27
| ChannelStore.GetByName | p99 | 71ms | 74ms | 3ms | 4.25
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 48ms | 50ms | 2ms | 4.19
| PostStore.GetPosts | p99 | 50ms | 52ms | 2ms | 4.02
| UserStore.Count | p99 | 85ms | 88ms | 3ms | 3.53
| PreferenceStore.Save | p99 | 185ms | 191ms | 6ms | 3.25
| ChannelStore.GetMemberCount | p99 | 92ms | 95ms | 3ms | 3.25
| UserStore.UpdateFailedPasswordAttempts | p99 | 69ms | 71ms | 2ms | 2.89
| TeamStore.SaveMember | p99 | 215ms | 221ms | 6ms | 2.79
| ChannelStore.CreateInitialSidebarCategories | p99 | 226ms | 232ms | 6ms | 2.66
| ThreadStore.GetTeamsUnreadForUser | p99 | 77ms | 79ms | 2ms | 2.60
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 93ms | 95ms | 2ms | 2.15
| SessionStore.Get | p99 | 100ms | 102ms | 2ms | 2.01
| PostStore.SearchPostsForUser | p99 | 926ms | 937ms | 11ms | 1.19
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -116.63
| ProductNoticesStore.GetViews | avg | 2ms | 0s | -2ms | -100.81
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -100.81
| PluginStore.SetWithOptions | avg | 5ms | 0s | -5ms | -93.48
| RetentionPolicyStore.GetAll | avg | 6ms | 1ms | -5ms | -89.20
| PluginStore.Delete | avg | 2ms | 0s | -2ms | -85.39
| PostPersistentNotificationStore.DeleteExpired | avg | 5ms | 2ms | -3ms | -64.49
| UserStore.GetProfilesInChannel | avg | 29ms | 11ms | -18ms | -62.36
| ChannelStore.AnalyticsCountAll | avg | 20ms | 11ms | -9ms | -45.35
| ScheduledPostStore.GetPendingScheduledPosts | avg | 7ms | 4ms | -3ms | -44.72
| TeamStore.GetTotalMemberCount | avg | 36ms | 20ms | -16ms | -44.02
| FileInfoStore.SetContent | avg | 10ms | 8ms | -2ms | -20.02
| ChannelStore.CreateSidebarCategory | avg | 23ms | 19ms | -4ms | -17.40
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.SetWithOptions | p99 | 10ms | 0s | -10ms | -101.01
| ProductNoticesStore.GetViews | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -100.96
| UserStore.GetProfilesInChannel | p99 | 241ms | 25ms | -216ms | -89.63
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 92ms | 24ms | -68ms | -74.32
| JobStore.UpdateOptimistically | p99 | 39ms | 15ms | -24ms | -61.54
| JobStore.GetNewestJobByStatusesAndType | p99 | 20ms | 8ms | -12ms | -60.76
| PostPersistentNotificationStore.DeleteExpired | p99 | 43ms | 21ms | -22ms | -51.16
| TeamStore.GetTotalMemberCount | p99 | 50ms | 25ms | -25ms | -50.25
| RetentionPolicyStore.GetAll | p99 | 10ms | 5ms | -5ms | -50.23
| PostAcknowledgementStore.GetForPost | p99 | 67ms | 43ms | -24ms | -35.83
| FileInfoStore.SetContent | p99 | 59ms | 38ms | -21ms | -35.44
| PostPriorityStore.GetForPost | p99 | 67ms | 45ms | -22ms | -32.84
| FileInfoStore.GetForPost | p99 | 12ms | 9ms | -3ms | -25.48
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 94ms | 74ms | -20ms | -21.30
| FileInfoStore.AttachToPost | p99 | 62ms | 50ms | -12ms | -19.40
| JobStore.UpdateStatusOptimistically | p99 | 22ms | 18ms | -4ms | -18.43
| JobStore.Save | p99 | 22ms | 18ms | -4ms | -18.43
| ChannelStore.GetChannelsByUser | p99 | 53ms | 50ms | -3ms | -5.61
| PropertyValueStore.SearchPropertyValues | p99 | 37ms | 35ms | -2ms | -5.43
| ThreadStore.GetThreadForUser | p99 | 44ms | 42ms | -2ms | -4.57
| UserStore.Search | p99 | 83ms | 81ms | -2ms | -2.42
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| login | avg | 154ms | 683ms | 529ms | 343.00
| createChannelBookmark | avg | 8ms | 22ms | 14ms | 175.42
| autocompleteChannelsForTeamForSearch | avg | 16ms | 27ms | 11ms | 69.03
| createChannel | avg | 200ms | 301ms | 101ms | 50.53
| logout | avg | 28ms | 33ms | 5ms | 17.87
| patchPost | avg | 26ms | 30ms | 4ms | 15.34
| deletePost | avg | 24ms | 27ms | 3ms | 12.43
| getClientConfig | avg | 18ms | 20ms | 2ms | 11.12
| setPostReminder | avg | 19ms | 21ms | 2ms | 10.34
| updateCategoriesForTeamForUser | avg | 52ms | 57ms | 5ms | 9.69
| getPostsForChannelAroundLastUnread | avg | 36ms | 39ms | 3ms | 8.43
| createGroupChannel | avg | 340ms | 365ms | 25ms | 7.36
| addTeamMember | avg | 1.025s | 1.078s | 53ms | 5.17
| searchPostsInTeam | avg | 96ms | 100ms | 4ms | 4.15
| addChannelMember | avg | 209ms | 217ms | 8ms | 3.83
| createUser | avg | 211ms | 219ms | 8ms | 3.80
| createDirectChannel | avg | 215ms | 218ms | 3ms | 1.39
| createPost | avg | 220ms | 223ms | 3ms | 1.36
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| login | p99 | 1.657s | 10s | 8.343s | 503.44
| getChannelUnread | p99 | 8ms | 41ms | 33ms | 409.94
| createChannelBookmark | p99 | 10ms | 49ms | 39ms | 391.85
| setPostReminder | p99 | 25ms | 49ms | 24ms | 96.56
| searchGroupChannels | p99 | 25ms | 47ms | 22ms | 89.54
| deletePost | p99 | 49ms | 90ms | 41ms | 82.97
| removeUserCustomStatus | p99 | 248ms | 452ms | 204ms | 82.17
| getJobsByType | p99 | 5ms | 9ms | 4ms | 80.81
| patchPost | p99 | 53ms | 89ms | 36ms | 68.14
| getTeamMember | p99 | 22ms | 34ms | 12ms | 54.94
| updatePreferences | p99 | 25ms | 36ms | 11ms | 44.03
| getUsers | p99 | 100ms | 142ms | 42ms | 42.12
| getChannel | p99 | 34ms | 48ms | 14ms | 41.64
| addChannelMember | p99 | 647ms | 835ms | 188ms | 29.04
| autocompleteChannelsForTeamForSearch | p99 | 72ms | 92ms | 20ms | 27.87
| createPost | p99 | 1.165s | 1.475s | 310ms | 26.60
| getPublicChannelsForTeam | p99 | 39ms | 48ms | 9ms | 23.08
| getFilePreview | p99 | 99ms | 119ms | 20ms | 20.15
| getPreferences | p99 | 69ms | 81ms | 12ms | 17.38
| getUsersByNames | p99 | 26ms | 30ms | 4ms | 15.68
| getTeamMembersForUser | p99 | 71ms | 81ms | 10ms | 14.00
| viewChannel | p99 | 142ms | 160ms | 18ms | 12.67
| getChannelStats | p99 | 64ms | 72ms | 8ms | 12.59
| getThreadsForUser | p99 | 66ms | 74ms | 8ms | 12.20
| listChannelBookmarksForChannel | p99 | 34ms | 38ms | 4ms | 11.87
| getTeamsUnreadForUser | p99 | 98ms | 109ms | 11ms | 11.20
| updateReadStateThreadByUser | p99 | 153ms | 170ms | 17ms | 11.10
| uploadFileStream | p99 | 1.313s | 1.452s | 139ms | 10.59
| createGroupChannel | p99 | 827ms | 912ms | 85ms | 10.27
| getUser | p99 | 100ms | 110ms | 10ms | 10.00
| addTeamMember | p99 | 3.929s | 4.311s | 382ms | 9.72
| getClientConfig | p99 | 184ms | 200ms | 16ms | 8.71
| getChannelMembersForUser | p99 | 65ms | 70ms | 5ms | 7.68
| getChannelMember | p99 | 155ms | 166ms | 11ms | 7.10
| listCPAFields | p99 | 74ms | 79ms | 5ms | 6.80
| autocompleteUsers | p99 | 166ms | 177ms | 11ms | 6.62
| getTeamsForUser | p99 | 64ms | 68ms | 4ms | 6.29
| getAllTeams | p99 | 78ms | 82ms | 4ms | 5.10
| getPostThread | p99 | 60ms | 63ms | 3ms | 5.02
| upsertDraft | p99 | 41ms | 43ms | 2ms | 4.91
| getChannelsForTeamForUser | p99 | 42ms | 44ms | 2ms | 4.81
| getChannelMembersForTeamForUser | p99 | 43ms | 45ms | 2ms | 4.66
| createUser | p99 | 869ms | 907ms | 38ms | 4.38
| getPostsForChannel | p99 | 220ms | 229ms | 9ms | 4.10
| getPostsForChannelAroundLastUnread | p99 | 240ms | 249ms | 9ms | 3.75
| saveReaction | p99 | 87ms | 89ms | 2ms | 2.31
| getCategoriesForTeamForUser | p99 | 97ms | 99ms | 2ms | 2.05
| getTeamScheduledPosts | p99 | 98ms | 100ms | 2ms | 2.03
| searchPostsInTeam | p99 | 930ms | 946ms | 16ms | 1.72
| createChannel | p99 | 488ms | 495ms | 7ms | 1.44
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUserByUsername | avg | 2ms | 0s | -2ms | -106.70
| getChannelMembers | avg | 3ms | 0s | -3ms | -103.58
| createCategoryForTeamForUser | avg | 25ms | 21ms | -4ms | -15.80
| getProfileImage | avg | 104ms | 97ms | -7ms | -6.74
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -100.96
| getUserByUsername | p99 | 5ms | 0s | -5ms | -100.39
| createCategoryForTeamForUser | p99 | 50ms | 25ms | -25ms | -50.25
| unfollowThreadByUser | p99 | 87ms | 76ms | -11ms | -12.62
| getChannelsForUser | p99 | 57ms | 53ms | -4ms | -7.01
| getDrafts | p99 | 33ms | 31ms | -2ms | -6.14
| listCPAValues | p99 | 37ms | 35ms | -2ms | -5.43
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 9ms | 1ms | 12.481
| |  P99| 55ms| 73ms | 18ms | 32.608
| BotStore.Get |  Avg| 3ms| 4ms | 1ms | 35.461
| |  P99| 10ms| 24ms | 14ms | 146.214
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -100.809
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 31ms | 6ms | 23.554
| ChannelBookmarkStore.Save |  Avg| 8ms| 14ms | 6ms | 77.471
| |  P99| 10ms| 25ms | 15ms | 150.713
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 7ms | 1ms | 15.721
| |  P99| 46ms| 49ms | 3ms | 6.546
| ChannelStore.AnalyticsCountAll |  Avg| 20ms| 11ms | -9ms | -45.353
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 34ms| 34ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 16ms| 27ms | 11ms | 69.430
| |  P99| 72ms| 92ms | 20ms | 27.874
| ChannelStore.CreateDirectChannel |  Avg| 27ms| 29ms | 2ms | 7.334
| |  P99| 197ms| 207ms | 10ms | 5.083
| ChannelStore.CreateInitialSidebarCategories |  Avg| 32ms| 34ms | 2ms | 6.304
| |  P99| 226ms| 232ms | 6ms | 2.657
| ChannelStore.CreateSidebarCategory |  Avg| 23ms| 19ms | -4ms | -17.398
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Get |  Avg| 4ms| 5ms | 1ms | 23.968
| |  P99| 46ms| 49ms | 3ms | 6.556
| ChannelStore.GetAllChannelMembersForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 45ms| 47ms | 2ms | 4.421
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 14ms| 13ms | -1ms | -7.406
| |  P99| 94ms| 74ms | -20ms | -21.299
| ChannelStore.GetByName |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 71ms| 74ms | 3ms | 4.247
| ChannelStore.GetChannelUnread |  Avg| 2ms| 3ms | 1ms | 52.885
| |  P99| 5ms| 41ms | 36ms | 727.273
| ChannelStore.GetChannels |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 43ms | 2ms | 4.895
| ChannelStore.GetChannelsByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 53ms| 50ms | -3ms | -5.608
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.210
| ChannelStore.GetFileCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 32ms | 7ms | 28.118
| ChannelStore.GetGuestCount |  Avg| 7ms| 8ms | 1ms | 13.871
| |  P99| 66ms| 77ms | 11ms | 16.636
| ChannelStore.GetMember |  Avg| 6ms| 7ms | 1ms | 15.896
| |  P99| 52ms| 60ms | 8ms | 15.276
| ChannelStore.GetMemberCount |  Avg| 21ms| 22ms | 1ms | 4.819
| |  P99| 92ms| 95ms | 3ms | 3.247
| ChannelStore.GetMemberForPost |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 27ms| 30ms | 3ms | 11.090
| ChannelStore.GetMemberLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 53ms | 4ms | 8.157
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -116.632
| |  P99| 5ms| 0s | -5ms | -100.958
| ChannelStore.GetMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 42ms| 44ms | 2ms | 4.745
| ChannelStore.GetMembersForUserWithPagination |  Avg| 7ms| 8ms | 1ms | 13.497
| |  P99| 62ms| 68ms | 6ms | 9.754
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 39.604
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 39ms| 47ms | 8ms | 20.517
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 11ms| 12ms | 1ms | 8.780
| |  P99| 93ms| 95ms | 2ms | 2.155
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 8ms | 2ms | 33.302
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 12ms| 11ms | -1ms | -8.215
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 4ms| 5ms | 1ms | 22.747
| |  P99| 45ms| 46ms | 1ms | 2.235
| ChannelStore.IsReadOnlyChannel |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 35ms | 4ms | 12.824
| ChannelStore.Save |  Avg| 13ms| 19ms | 6ms | 47.595
| |  P99| 62ms| 213ms | 151ms | 243.536
| ChannelStore.SaveMember |  Avg| 49ms| 51ms | 2ms | 4.123
| |  P99| 247ms| 281ms | 34ms | 13.747
| ChannelStore.SearchGroupChannels |  Avg| 4ms| 5ms | 1ms | 25.966
| |  P99| 25ms| 46ms | 21ms | 85.473
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.086
| ChannelStore.UpdateSidebarCategories |  Avg| 37ms| 40ms | 3ms | 8.048
| |  P99| 88ms| 96ms | 8ms | 9.138
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 5ms| 6ms | 1ms | 19.794
| |  P99| 43ms| 55ms | 12ms | 27.587
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 20ms | 7ms | 53.640
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 6ms| 9ms | 3ms | 48.567
| |  P99| 47ms| 90ms | 43ms | 92.470
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.383
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 32ms| 31ms | -1ms | -3.165
| DraftStore.Upsert |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 34ms| 36ms | 2ms | 5.818
| EmojiStore.GetByName |  Avg| 2ms| 3ms | 1ms | 40.212
| |  P99| 25ms| 24ms | -1ms | -4.013
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 9ms| 8ms | -1ms | -11.340
| |  P99| 62ms| 50ms | -12ms | -19.401
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 52.049
| FileInfoStore.GetByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 36ms | 11ms | 44.079
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 9ms | -3ms | -25.482
| FileInfoStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 46ms | 2ms | 4.576
| FileInfoStore.SetContent |  Avg| 10ms| 8ms | -2ms | -20.021
| |  P99| 59ms| 38ms | -21ms | -35.443
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 49ms | 3ms | 6.471
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 62ms | 12ms | 24.198
| GroupStore.GetGroups |  Avg| 3ms| 4ms | 1ms | 28.963
| |  P99| 37ms| 39ms | 2ms | 5.449
| JobStore.GetAllByStatus |  Avg| 3ms| 4ms | 1ms | 32.960
| |  P99| 28ms| 44ms | 16ms | 57.291
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 42.820
| |  P99| 16ms| 21ms | 5ms | 30.960
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -38.774
| |  P99| 20ms| 8ms | -12ms | -60.759
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -21.447
| |  P99| 22ms| 18ms | -4ms | -18.433
| JobStore.UpdateOptimistically |  Avg| 5ms| 4ms | -1ms | -20.732
| |  P99| 39ms| 15ms | -24ms | -61.538
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 4ms | -1ms | -20.987
| |  P99| 22ms| 18ms | -4ms | -18.433
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 19ms | 9ms | 92.551
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.195
| PluginStore.Delete |  Avg| 2ms| 0s | -2ms | -85.390
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 120.879
| PluginStore.SetWithOptions |  Avg| 5ms| 0s | -5ms | -93.477
| |  P99| 10ms| 0s | -10ms | -101.010
| PostAcknowledgementStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -22.652
| |  P99| 67ms| 43ms | -24ms | -35.826
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 4ms | 1ms | 29.305
| |  P99| 35ms| 38ms | 3ms | 8.472
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 2ms | -3ms | -64.490
| |  P99| 43ms| 21ms | -22ms | -51.163
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.849
| PostPriorityStore.GetForPost |  Avg| 4ms| 3ms | -1ms | -25.622
| |  P99| 67ms| 45ms | -22ms | -32.841
| PostPriorityStore.GetForPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 41ms | 2ms | 5.105
| PostStore.AnalyticsPostCount |  Avg| 264ms| 275ms | 11ms | 4.174
| |  P99| 498ms| 990ms | 492ms | 98.894
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 2ms | 1ms | 83.261
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 16ms| 19ms | 3ms | 18.404
| |  P99| 25ms| 47ms | 22ms | 88.531
| PostStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 40ms| 48ms | 8ms | 19.817
| PostStore.GetEtag |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 48ms | 3ms | 6.623
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 6ms | 1ms | 18.843
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 4ms | 1ms | 29.590
| |  P99| 29ms| 33ms | 4ms | 13.897
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 14ms| 13ms | -1ms | -7.270
| |  P99| 92ms| 92ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 7ms | 1ms | 15.640
| |  P99| 50ms| 52ms | 2ms | 4.023
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 36ms | 3ms | 9.037
| PostStore.GetPostsByThread |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 50ms| 57ms | 7ms | 13.920
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 85.637
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 17ms| 18ms | 1ms | 5.849
| |  P99| 97ms| 132ms | 35ms | 35.945
| PostStore.SearchPostsForUser |  Avg| 87ms| 90ms | 3ms | 3.449
| |  P99| 926ms| 937ms | 11ms | 1.187
| PostStore.SetPostReminder |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 10ms| 24ms | 14ms | 140.704
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 26ms| 25ms | -1ms | -3.845
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 7ms | 3ms | 66.775
| |  P99| 47ms| 90ms | 43ms | 92.470
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 32ms | 4ms | 14.132
| PreferenceStore.GetAll |  Avg| 7ms| 8ms | 1ms | 14.212
| |  P99| 65ms| 78ms | 13ms | 20.090
| PreferenceStore.Save |  Avg| 21ms| 22ms | 1ms | 4.709
| |  P99| 185ms| 191ms | 6ms | 3.250
| ProductNoticesStore.ClearOldNotices |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 0s | -2ms | -100.814
| |  P99| 5ms| 0s | -5ms | -101.010
| ProductNoticesStore.View |  Avg| 64ms| 68ms | 4ms | 6.286
| |  P99| 416ms| 443ms | 27ms | 6.487
| PropertyFieldStore.SearchPropertyFields |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 54ms| 64ms | 10ms | 18.595
| PropertyValueStore.SearchPropertyValues |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 37ms| 35ms | -2ms | -5.432
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 38ms | 15ms | 64.621
| RetentionPolicyStore.GetAll |  Avg| 6ms| 1ms | -5ms | -89.203
| |  P99| 10ms| 5ms | -5ms | -50.228
| RetentionPolicyStore.GetCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.787
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 7ms| 4ms | -3ms | -44.719
| |  P99| 92ms| 24ms | -68ms | -74.317
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 54ms| 63ms | 9ms | 16.663
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 4ms| 3ms | -1ms | -27.139
| |  P99| 22ms| 22ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 1ms| 0s | -1ms | -72.817
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 13ms| 14ms | 1ms | 7.645
| |  P99| 100ms| 102ms | 2ms | 2.007
| SessionStore.GetLRUSessions |  Avg| 6ms| 7ms | 1ms | 17.926
| |  P99| 52ms| 68ms | 16ms | 30.808
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 18ms | 5ms | 38.939
| SessionStore.Remove |  Avg| 3ms| 4ms | 1ms | 29.384
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 13ms| 15ms | 2ms | 15.151
| |  P99| 95ms| 100ms | 5ms | 5.263
| SessionStore.UpdateLastActivityAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.470
| SharedChannelStore.HasChannel |  Avg| 2ms| 3ms | 1ms | 40.205
| |  P99| 25ms| 30ms | 5ms | 20.205
| StatusStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 49ms| 53ms | 4ms | 8.230
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.470
| StatusStore.SaveOrUpdate |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 40ms| 41ms | 1ms | 2.505
| StatusStore.SaveOrUpdateMany |  Avg| 6ms| 8ms | 2ms | 31.353
| |  P99| 25ms| 57ms | 32ms | 128.768
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 5ms | -1ms | -17.069
| |  P99| 78ms| 78ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 6ms| 7ms | 1ms | 16.051
| |  P99| 61ms| 68ms | 7ms | 11.450
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 2ms | 1ms | 72.061
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.389
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 35ms | -1ms | -2.755
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 60ms| 69ms | 9ms | 15.012
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 64ms | 14ms | 27.833
| TeamStore.GetMember |  Avg| 5ms| 6ms | 1ms | 19.022
| |  P99| 47ms| 49ms | 2ms | 4.272
| TeamStore.GetTeamsByUserId |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 61ms| 65ms | 4ms | 6.526
| TeamStore.GetTeamsForUser |  Avg| 6ms| 7ms | 1ms | 17.058
| |  P99| 52ms| 67ms | 15ms | 29.120
| TeamStore.GetTotalMemberCount |  Avg| 36ms| 20ms | -16ms | -44.016
| |  P99| 50ms| 25ms | -25ms | -50.251
| TeamStore.SaveMember |  Avg| 36ms| 38ms | 2ms | 5.507
| |  P99| 215ms| 221ms | 6ms | 2.792
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.568
| ThreadStore.GetTeamsUnreadForUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 79ms | 2ms | 2.603
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.571
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 38ms | 5ms | 15.028
| ThreadStore.GetTotalThreads |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 51ms | 3ms | 6.239
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 5ms | 1ms | 22.925
| |  P99| 44ms| 47ms | 3ms | 6.773
| ThreadStore.GetTotalUnreadThreads |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 48ms| 51ms | 3ms | 6.262
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 5ms| 6ms | 1ms | 19.348
| |  P99| 48ms| 50ms | 2ms | 4.189
| ThreadStore.MaintainMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 50ms| 57ms | 7ms | 13.894
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 4ms | 1ms | 30.890
| |  P99| 18ms| 41ms | 23ms | 125.004
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 16ms | 5ms | 44.497
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 26.036
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 4ms | 2ms | 101.928
| |  P99| 5ms| 23ms | 18ms | 363.527
| UserStore.AnalyticsActiveCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 39ms| 39ms | 0s | 0.000
| |  P99| 188ms| 198ms | 10ms | 5.315
| UserStore.Count |  Avg| 16ms| 17ms | 1ms | 6.095
| |  P99| 85ms| 88ms | 3ms | 3.534
| UserStore.Get |  Avg| 4ms| 5ms | 1ms | 23.050
| |  P99| 45ms| 49ms | 4ms | 8.910
| UserStore.GetAllProfiles |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 49ms | 4ms | 8.862
| UserStore.GetAllProfilesInChannel |  Avg| 210ms| 216ms | 6ms | 2.856
| |  P99| 823ms| 875ms | 52ms | 6.316
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 38ms | 14ms | 58.517
| UserStore.GetForLogin |  Avg| 6ms| 7ms | 1ms | 16.141
| |  P99| 59ms| 75ms | 16ms | 27.218
| UserStore.GetMany |  Avg| 2ms| 3ms | 1ms | 48.937
| |  P99| 5ms| 20ms | 15ms | 303.030
| UserStore.GetProfileByIds |  Avg| 4ms| 5ms | 1ms | 23.215
| |  P99| 46ms| 48ms | 2ms | 4.392
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.096
| UserStore.GetProfilesInChannel |  Avg| 29ms| 11ms | -18ms | -62.361
| |  P99| 241ms| 25ms | -216ms | -89.627
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 5ms | 1ms | 23.188
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.754
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 34ms | 3ms | 9.674
| UserStore.Save |  Avg| 93ms| 94ms | 1ms | 1.079
| |  P99| 249ms| 312ms | 63ms | 25.251
| UserStore.Search |  Avg| 28ms| 27ms | -1ms | -3.618
| |  P99| 83ms| 81ms | -2ms | -2.416
| UserStore.Update |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 41ms| 85ms | 44ms | 106.666
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 9ms | 1ms | 11.992
| |  P99| 69ms| 71ms | 2ms | 2.887
| UserStore.UpdateLastLogin |  Avg| 8ms| 9ms | 1ms | 12.011
| |  P99| 48ms| 63ms | 15ms | 30.984
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 47ms| 53ms | 6ms | 12.638
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 56ms| 60ms | 4ms | 7.159
| WebhookStore.GetOutgoingByTeam |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 46ms| 47ms | 1ms | 2.190
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 209ms| 217ms | 8ms | 3.830
| | P99| 647ms| 835ms | 188ms | 29.036
| addTeamMember | Avg| 1.025s| 1.078s | 53ms | 5.170
| | P99| 3.929s| 4.311s | 382ms | 9.724
| autocompleteChannelsForTeamForSearch | Avg| 16ms| 27ms | 11ms | 69.033
| | P99| 72ms| 92ms | 20ms | 27.874
| autocompleteUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 166ms| 177ms | 11ms | 6.622
| createCategoryForTeamForUser | Avg| 25ms| 21ms | -4ms | -15.798
| | P99| 50ms| 25ms | -25ms | -50.251
| createChannel | Avg| 200ms| 301ms | 101ms | 50.531
| | P99| 488ms| 495ms | 7ms | 1.436
| createChannelBookmark | Avg| 8ms| 22ms | 14ms | 175.417
| | P99| 10ms| 49ms | 39ms | 391.854
| createDirectChannel | Avg| 215ms| 218ms | 3ms | 1.393
| | P99| 493ms| 492ms | -1ms | -0.203
| createGroupChannel | Avg| 340ms| 365ms | 25ms | 7.356
| | P99| 827ms| 912ms | 85ms | 10.272
| createPost | Avg| 220ms| 223ms | 3ms | 1.364
| | P99| 1.165s| 1.475s | 310ms | 26.602
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 10.656
| createUser | Avg| 211ms| 219ms | 8ms | 3.799
| | P99| 869ms| 907ms | 38ms | 4.375
| deleteDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 21ms | 1ms | 5.077
| deletePost | Avg| 24ms| 27ms | 3ms | 12.429
| | P99| 49ms| 90ms | 41ms | 82.968
| followThreadByUser | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 7ms| 8ms | 1ms | 14.412
| | P99| 78ms| 82ms | 4ms | 5.097
| getCategoriesForTeamForUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 97ms| 99ms | 2ms | 2.053
| getChannel | Avg| 6ms| 7ms | 1ms | 17.888
| | P99| 34ms| 48ms | 14ms | 41.635
| getChannelMember | Avg| 15ms| 16ms | 1ms | 6.799
| | P99| 155ms| 166ms | 11ms | 7.101
| getChannelMembers | Avg| 3ms| 0s | -3ms | -103.585
| | P99| 5ms| 0s | -5ms | -100.958
| getChannelMembersForTeamForUser | Avg| 4ms| 5ms | 1ms | 22.629
| | P99| 43ms| 45ms | 2ms | 4.662
| getChannelMembersForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 65ms| 70ms | 5ms | 7.681
| getChannelStats | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 64ms| 72ms | 8ms | 12.585
| getChannelUnread | Avg| 2ms| 3ms | 1ms | 47.935
| | P99| 8ms| 41ms | 33ms | 409.935
| getChannelsForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 42ms| 44ms | 2ms | 4.814
| getChannelsForUser | Avg| 6ms| 7ms | 1ms | 15.780
| | P99| 57ms| 53ms | -4ms | -7.012
| getClientConfig | Avg| 18ms| 20ms | 2ms | 11.120
| | P99| 184ms| 200ms | 16ms | 8.709
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 33ms| 31ms | -2ms | -6.140
| getFilePreview | Avg| 41ms| 42ms | 1ms | 2.414
| | P99| 99ms| 119ms | 20ms | 20.145
| getFileThumbnail | Avg| 35ms| 36ms | 1ms | 2.846
| | P99| 97ms| 98ms | 1ms | 1.035
| getFilteredUsersStats | Avg| 11ms| 10ms | -1ms | -9.341
| | P99| 25ms| 25ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.808
| getPostThread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 60ms| 63ms | 3ms | 5.019
| getPostsForChannel | Avg| 25ms| 26ms | 1ms | 4.079
| | P99| 220ms| 229ms | 9ms | 4.096
| getPostsForChannelAroundLastUnread | Avg| 36ms| 39ms | 3ms | 8.429
| | P99| 240ms| 249ms | 9ms | 3.751
| getPreferences | Avg| 7ms| 8ms | 1ms | 13.722
| | P99| 69ms| 81ms | 12ms | 17.382
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 104ms| 97ms | -7ms | -6.742
| | P99| 481ms| 480ms | -1ms | -0.208
| getPublicChannelsForTeam | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 39ms| 48ms | 9ms | 23.082
| getRolesByNames | Avg| 4ms| 3ms | -1ms | -25.041
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamMember | Avg| 3ms| 4ms | 1ms | 30.035
| | P99| 22ms| 34ms | 12ms | 54.941
| getTeamMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 71ms| 81ms | 10ms | 13.996
| getTeamScheduledPosts | Avg| 12ms| 13ms | 1ms | 8.550
| | P99| 98ms| 100ms | 2ms | 2.034
| getTeamStats | Avg| 37ms| 36ms | -1ms | -2.739
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 6ms| 7ms | 1ms | 16.500
| | P99| 64ms| 68ms | 4ms | 6.286
| getTeamsUnreadForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 98ms| 109ms | 11ms | 11.203
| getThreadsForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 66ms| 74ms | 8ms | 12.205
| getUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 100ms| 110ms | 10ms | 10.001
| getUserByUsername | Avg| 2ms| 0s | -2ms | -106.699
| | P99| 5ms| 0s | -5ms | -100.386
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 9ms| 10ms | 1ms | 11.279
| | P99| 100ms| 142ms | 42ms | 42.115
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 26ms| 30ms | 4ms | 15.679
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 74ms| 79ms | 5ms | 6.802
| listCPAValues | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 37ms| 35ms | -2ms | -5.432
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 38ms | 4ms | 11.866
| login | Avg| 154ms| 683ms | 529ms | 343.002
| | P99| 1.657s| 10s | 8.343s | 503.441
| logout | Avg| 28ms| 33ms | 5ms | 17.865
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 26ms| 30ms | 4ms | 15.345
| | P99| 53ms| 89ms | 36ms | 68.136
| removeUserCustomStatus | Avg| 140ms| 140ms | 0s | 0.000
| | P99| 248ms| 452ms | 204ms | 82.166
| root | Avg| 0s| 1ms | 1ms | 342.428
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 87ms| 89ms | 2ms | 2.310
| searchAllChannels | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 5ms | 1ms | 25.401
| | P99| 25ms| 47ms | 22ms | 89.544
| searchPostsInTeam | Avg| 96ms| 100ms | 4ms | 4.149
| | P99| 930ms| 946ms | 16ms | 1.720
| searchUsers | Avg| 29ms| 29ms | 0s | 0.000
| | P99| 84ms| 84ms | 0s | 0.000
| setPostReminder | Avg| 19ms| 21ms | 2ms | 10.343
| | P99| 25ms| 49ms | 24ms | 96.559
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 17ms| 16ms | -1ms | -5.994
| | P99| 87ms| 76ms | -11ms | -12.622
| updateCategoriesForTeamForUser | Avg| 52ms| 57ms | 5ms | 9.685
| | P99| 99ms| 99ms | 0s | 0.000
| updatePreferences | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 36ms | 11ms | 44.026
| updateReadStateThreadByUser | Avg| 42ms| 41ms | -1ms | -2.396
| | P99| 153ms| 170ms | 17ms | 11.099
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 491ms| 489ms | -2ms | -0.408
| | P99| 1.313s| 1.452s | 139ms | 10.589
| upsertDraft | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 41ms| 43ms | 2ms | 4.906
| viewChannel | Avg| 15ms| 16ms | 1ms | 6.517
| | P99| 142ms| 160ms | 18ms | 12.667
