### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PreferenceStore.DeleteCategoryAndName | avg | 1ms | 4ms | 3ms | 325.50
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 3ms | 9ms | 6ms | 198.88
| PluginStore.List | avg | 2ms | 4ms | 2ms | 107.96
| UserAccessTokenStore.GetByToken | avg | 2ms | 4ms | 2ms | 101.29
| UserStore.Save | avg | 77ms | 150ms | 73ms | 95.23
| BotStore.Get | avg | 2ms | 4ms | 2ms | 90.77
| LinkMetadataStore.Save | avg | 2ms | 4ms | 2ms | 81.84
| UserStore.Update | avg | 5ms | 8ms | 3ms | 55.35
| PreferenceStore.Save | avg | 8ms | 12ms | 4ms | 49.33
| ChannelStore.GetGuestCount | avg | 4ms | 6ms | 2ms | 44.59
| ProductNoticesStore.View | avg | 24ms | 34ms | 10ms | 41.73
| UserStore.GetProfilesInChannel | avg | 20ms | 28ms | 8ms | 39.94
| ChannelStore.CreateSidebarCategory | avg | 8ms | 11ms | 3ms | 39.84
| ChannelStore.CreateInitialSidebarCategories | avg | 12ms | 16ms | 4ms | 34.06
| ChannelStore.AnalyticsCountAll | avg | 15ms | 20ms | 5ms | 32.47
| SessionStore.Get | avg | 7ms | 9ms | 2ms | 30.65
| SessionStore.Save | avg | 7ms | 9ms | 2ms | 27.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 8ms | 10ms | 2ms | 25.09
| ChannelStore.SaveMember | avg | 31ms | 36ms | 5ms | 16.21
| UserStore.GetAllProfilesInChannel | avg | 172ms | 185ms | 13ms | 7.54
| PostStore.AnalyticsPostCount | avg | 132ms | 137ms | 5ms | 3.79
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.List | p99 | 5ms | 82ms | 77ms | 1555.56
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 9ms | 94ms | 85ms | 904.25
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 47ms | 42ms | 848.48
| LinkMetadataStore.Save | p99 | 5ms | 41ms | 36ms | 727.27
| UserStore.Update | p99 | 21ms | 84ms | 63ms | 297.52
| UserStore.GetMany | p99 | 5ms | 19ms | 14ms | 282.73
| ReactionStore.GetForPost | p99 | 10ms | 30ms | 20ms | 206.55
| UserAccessTokenStore.GetByToken | p99 | 9ms | 24ms | 15ms | 162.09
| ChannelStore.CreateSidebarCategory | p99 | 10ms | 25ms | 15ms | 150.75
| BotStore.Get | p99 | 9ms | 22ms | 13ms | 142.08
| PostStore.GetPostReminders | p99 | 9ms | 22ms | 13ms | 142.08
| JobStore.Save | p99 | 9ms | 21ms | 12ms | 129.50
| UserStore.GetByUsername | p99 | 15ms | 33ms | 18ms | 123.51
| JobStore.UpdateStatusOptimistically | p99 | 19ms | 38ms | 19ms | 102.44
| FileInfoStore.GetByIds | p99 | 12ms | 23ms | 11ms | 94.41
| UserStore.Save | p99 | 234ms | 454ms | 220ms | 94.01
| PostPersistentNotificationStore.Get | p99 | 23ms | 43ms | 20ms | 87.05
| ChannelStore.CreateInitialSidebarCategories | p99 | 96ms | 178ms | 82ms | 85.59
| ScheduledPostStore.CreateScheduledPost | p99 | 5ms | 9ms | 4ms | 80.81
| ThreadStore.MaintainMembership | p99 | 19ms | 34ms | 15ms | 80.07
| EmojiStore.GetByName | p99 | 10ms | 18ms | 8ms | 77.07
| SessionStore.UpdateLastActivityAt | p99 | 10ms | 17ms | 7ms | 72.64
| StatusStore.UpdateLastActivityAt | p99 | 10ms | 17ms | 7ms | 69.34
| TeamStore.Get | p99 | 10ms | 17ms | 7ms | 67.39
| JobStore.GetAllByStatus | p99 | 25ms | 41ms | 16ms | 64.50
| ChannelStore.GetSidebarCategory | p99 | 23ms | 38ms | 15ms | 64.38
| PostStore.GetPostIdBeforeTime | p99 | 13ms | 21ms | 8ms | 61.84
| PostPersistentNotificationStore.GetSingle | p99 | 9ms | 14ms | 5ms | 54.88
| ClusterDiscoveryStore.SetLastPingAt | p99 | 18ms | 28ms | 10ms | 54.57
| PostAcknowledgementStore.GetForPost | p99 | 26ms | 40ms | 14ms | 54.37
| DraftStore.Delete | p99 | 6ms | 9ms | 3ms | 54.36
| PostStore.GetPostIdAfterTime | p99 | 26ms | 40ms | 14ms | 53.87
| ChannelStore.CreateDirectChannel | p99 | 86ms | 132ms | 46ms | 53.65
| ChannelStore.Get | p99 | 25ms | 37ms | 12ms | 48.51
| SessionStore.Save | p99 | 52ms | 77ms | 25ms | 48.31
| ThreadStore.GetMembershipForUser | p99 | 13ms | 19ms | 6ms | 47.67
| UserStore.Get | p99 | 23ms | 33ms | 10ms | 43.05
| PostStore.GetEtag | p99 | 26ms | 37ms | 11ms | 42.37
| PropertyValueStore.SearchPropertyValues | p99 | 15ms | 21ms | 6ms | 41.21
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 24ms | 34ms | 10ms | 41.19
| UserStore.GetProfilesByUsernames | p99 | 15ms | 21ms | 6ms | 40.56
| PostStore.Save | p99 | 55ms | 77ms | 22ms | 40.28
| ChannelStore.UpdateLastViewedAt | p99 | 15ms | 21ms | 6ms | 39.87
| UserStore.GetProfileByIds | p99 | 25ms | 35ms | 10ms | 39.68
| ChannelStore.GetFileCount | p99 | 16ms | 22ms | 6ms | 37.80
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 16ms | 22ms | 6ms | 36.95
| FileInfoStore.SetContent | p99 | 45ms | 61ms | 16ms | 35.60
| ChannelStore.Save | p99 | 42ms | 56ms | 14ms | 33.47
| ChannelStore.GetMembersForUser | p99 | 24ms | 32ms | 8ms | 33.21
| ChannelStore.IncrementMentionCount | p99 | 24ms | 32ms | 8ms | 33.14
| FileInfoStore.Get | p99 | 6ms | 8ms | 2ms | 32.95
| SystemStore.GetByName | p99 | 31ms | 41ms | 10ms | 32.56
| PostStore.Get | p99 | 25ms | 33ms | 8ms | 32.18
| UserStore.GetAllProfiles | p99 | 26ms | 34ms | 8ms | 30.98
| UserStore.UpdateLastLogin | p99 | 32ms | 42ms | 10ms | 30.98
| ThreadStore.UpdateMembership | p99 | 6ms | 8ms | 2ms | 30.91
| ProductNoticesStore.View | p99 | 217ms | 283ms | 66ms | 30.40
| PostPriorityStore.GetForPost | p99 | 27ms | 35ms | 8ms | 30.19
| ChannelStore.GetChannels | p99 | 23ms | 30ms | 7ms | 29.81
| ChannelStore.GetMember | p99 | 34ms | 44ms | 10ms | 29.21
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 31ms | 40ms | 9ms | 28.73
| ThreadStore.GetTotalUnreadMentions | p99 | 31ms | 40ms | 9ms | 28.61
| ThreadStore.GetThreadForUser | p99 | 25ms | 32ms | 7ms | 28.36
| PreferenceStore.Get | p99 | 18ms | 23ms | 5ms | 27.35
| FileInfoStore.AttachToPost | p99 | 22ms | 28ms | 6ms | 27.20
| UserStore.UpdateUpdateAt | p99 | 30ms | 38ms | 8ms | 26.72
| ThreadStore.GetTotalThreads | p99 | 34ms | 43ms | 9ms | 26.54
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 64ms | 81ms | 17ms | 26.51
| ThreadStore.GetTotalUnreadThreads | p99 | 34ms | 43ms | 9ms | 26.11
| StatusStore.SaveOrUpdate | p99 | 28ms | 35ms | 7ms | 25.20
| DraftStore.Get | p99 | 8ms | 10ms | 2ms | 25.12
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 35ms | 43ms | 8ms | 23.14
| SessionStore.Get | p99 | 69ms | 85ms | 16ms | 23.13
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 18ms | 22ms | 4ms | 22.67
| ChannelStore.GetMemberForPost | p99 | 18ms | 22ms | 4ms | 22.65
| PostPriorityStore.GetForPosts | p99 | 23ms | 28ms | 5ms | 21.89
| PreferenceStore.Save | p99 | 83ms | 101ms | 18ms | 21.76
| TeamStore.GetMember | p99 | 33ms | 40ms | 7ms | 21.41
| StatusStore.Get | p99 | 35ms | 42ms | 7ms | 20.20
| ThreadStore.GetThreadsForUser | p99 | 20ms | 24ms | 4ms | 19.85
| UserStore.GetUnreadCount | p99 | 15ms | 18ms | 3ms | 19.77
| SessionStore.GetLRUSessions | p99 | 37ms | 44ms | 7ms | 19.10
| ThreadStore.GetTeamsUnreadForUser | p99 | 43ms | 51ms | 8ms | 18.61
| AuditStore.Save | p99 | 38ms | 45ms | 7ms | 18.57
| UserTermsOfServiceStore.GetByUser | p99 | 38ms | 45ms | 7ms | 18.55
| PostStore.GetPosts | p99 | 38ms | 45ms | 7ms | 18.38
| TeamStore.GetTeamsByUserId | p99 | 39ms | 46ms | 7ms | 17.94
| ThreadStore.GetThreadFollowers | p99 | 17ms | 20ms | 3ms | 17.15
| DraftStore.Upsert | p99 | 19ms | 22ms | 3ms | 15.67
| ChannelStore.GetAllChannelMembersForUser | p99 | 32ms | 37ms | 5ms | 15.64
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 39ms | 45ms | 6ms | 15.53
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 39ms | 45ms | 6ms | 15.47
| ChannelStore.GetChannelsByUser | p99 | 39ms | 45ms | 6ms | 15.36
| PropertyFieldStore.SearchPropertyFields | p99 | 39ms | 45ms | 6ms | 15.35
| TeamStore.GetAllPage | p99 | 40ms | 46ms | 6ms | 15.15
| TeamStore.GetTeamsForUser | p99 | 40ms | 46ms | 6ms | 15.11
| GroupStore.GetByName | p99 | 41ms | 47ms | 6ms | 14.76
| UserStore.GetForLogin | p99 | 41ms | 47ms | 6ms | 14.73
| ChannelStore.GetMembersForUserWithPagination | p99 | 41ms | 47ms | 6ms | 14.60
| PostStore.GetPostsBefore | p99 | 21ms | 24ms | 3ms | 14.48
| ChannelStore.GetGuestCount | p99 | 42ms | 48ms | 6ms | 14.18
| ChannelStore.SaveMember | p99 | 199ms | 227ms | 28ms | 14.11
| PostAcknowledgementStore.GetForPosts | p99 | 22ms | 25ms | 3ms | 13.60
| ChannelStore.GetMemberLastViewedAt | p99 | 37ms | 42ms | 5ms | 13.42
| GroupStore.GetGroups | p99 | 23ms | 26ms | 3ms | 13.16
| WebhookStore.GetOutgoingByTeam | p99 | 32ms | 36ms | 4ms | 12.44
| UserStore.Count | p99 | 65ms | 72ms | 7ms | 10.77
| FileInfoStore.Save | p99 | 20ms | 22ms | 2ms | 9.79
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 77ms | 83ms | 6ms | 7.76
| UserStore.Search | p99 | 67ms | 72ms | 5ms | 7.47
| ChannelStore.GetMemberCount | p99 | 78ms | 83ms | 5ms | 6.43
| UserStore.UpdateFailedPasswordAttempts | p99 | 43ms | 45ms | 2ms | 4.61
| PreferenceStore.GetAll | p99 | 44ms | 46ms | 2ms | 4.57
| ChannelStore.GetByName | p99 | 47ms | 49ms | 2ms | 4.27
| UserStore.GetAllProfilesInChannel | p99 | 492ms | 509ms | 17ms | 3.45
| UserStore.GetProfilesInChannel | p99 | 234ms | 241ms | 7ms | 3.00
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SchemeStore.GetAllPage | avg | 2ms | 0s | -2ms | -131.08
| RetentionPolicyStore.GetAll | avg | 2ms | 0s | -2ms | -123.90
| EmojiStore.Search | avg | 2ms | 0s | -2ms | -109.61
| ChannelBookmarkStore.Delete | avg | 4ms | 0s | -4ms | -103.28
| SharedChannelStore.HasChannel | avg | 2ms | 0s | -2ms | -98.81
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -98.72
| SystemStore.PermanentDeleteByName | avg | 2ms | 0s | -2ms | -93.97
| ChannelStore.IsReadOnlyChannel | avg | 2ms | 0s | -2ms | -91.86
| BotStore.GetAll | avg | 2ms | 0s | -2ms | -87.91
| SystemStore.SaveOrUpdate | avg | 2ms | 0s | -2ms | -84.59
| PluginStore.SetWithOptions | avg | 2ms | 0s | -2ms | -80.07
| PostStore.Delete | avg | 10ms | 8ms | -2ms | -20.75
| ProductNoticesStore.ClearOldNotices | avg | 17ms | 15ms | -2ms | -12.07
| TeamStore.GetTotalMemberCount | avg | 37ms | 35ms | -2ms | -5.46
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SharedChannelStore.HasChannel | p99 | 16ms | 0s | -16ms | -102.47
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -102.04
| ChannelStore.IsReadOnlyChannel | p99 | 19ms | 0s | -19ms | -101.21
| RetentionPolicyStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| SchemeStore.GetAllPage | p99 | 5ms | 0s | -5ms | -101.01
| RetentionPolicyStore.GetCount | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.SetWithOptions | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.SaveOrUpdate | p99 | 5ms | 0s | -5ms | -101.01
| BotStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| PluginStore.Delete | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.PermanentDeleteByName | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelUnread | p99 | 41ms | 5ms | -36ms | -88.89
| RoleStore.ChannelHigherScopedPermissions | p99 | 20ms | 5ms | -15ms | -76.26
| JobStore.UpdateStatus | p99 | 78ms | 21ms | -57ms | -72.62
| JobStore.UpdateOptimistically | p99 | 77ms | 30ms | -47ms | -61.05
| PostPersistentNotificationStore.DeleteExpired | p99 | 23ms | 9ms | -14ms | -60.94
| SessionStore.Remove | p99 | 22ms | 9ms | -13ms | -59.09
| PostStore.GetPostsAfter | p99 | 19ms | 9ms | -10ms | -51.81
| StatusStore.UpdateExpiredDNDStatuses | p99 | 55ms | 28ms | -27ms | -48.65
| ChannelStore.GetTeamChannels | p99 | 47ms | 25ms | -22ms | -46.32
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 9ms | 5ms | -4ms | -43.72
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 9ms | 5ms | -4ms | -43.72
| JobStore.GetCountByStatusAndType | p99 | 35ms | 21ms | -14ms | -39.72
| StatusStore.SaveOrUpdateMany | p99 | 40ms | 25ms | -15ms | -37.27
| ThreadStore.Get | p99 | 8ms | 5ms | -3ms | -35.93
| ChannelStore.GetPinnedPostCount | p99 | 10ms | 8ms | -2ms | -20.71
| JobStore.GetNewestJobByStatusesAndType | p99 | 25ms | 20ms | -5ms | -20.20
| DraftStore.GetDraftsForUser | p99 | 23ms | 21ms | -2ms | -8.77
| UserStore.AutocompleteUsersInChannel | p99 | 195ms | 191ms | -4ms | -2.05
| TeamStore.SaveMember | p99 | 98ms | 96ms | -2ms | -2.03
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| login | avg | 74ms | 864ms | 790ms | 1065.78
| createUser | avg | 152ms | 243ms | 91ms | 59.95
| createCategoryForTeamForUser | avg | 11ms | 17ms | 6ms | 53.89
| getAnalytics | avg | 30ms | 44ms | 14ms | 46.81
| getChannelsForUser | avg | 4ms | 6ms | 2ms | 44.70
| getUsers | avg | 5ms | 7ms | 2ms | 40.56
| getUser | avg | 5ms | 7ms | 2ms | 40.51
| getClientConfig | avg | 6ms | 8ms | 2ms | 35.27
| getPostsForChannelAroundLastUnread | avg | 21ms | 27ms | 6ms | 28.08
| getTeamsUnreadForUser | avg | 7ms | 9ms | 2ms | 27.95
| getTeamScheduledPosts | avg | 8ms | 10ms | 2ms | 25.84
| getChannelMember | avg | 8ms | 10ms | 2ms | 25.23
| addTeamMember | avg | 685ms | 773ms | 88ms | 12.84
| getPostsForChannel | avg | 20ms | 22ms | 2ms | 9.77
| createPost | avg | 153ms | 162ms | 9ms | 5.87
| removeUserCustomStatus | avg | 116ms | 122ms | 6ms | 5.18
| searchPostsInTeam | avg | 86ms | 89ms | 3ms | 3.49
| createDirectChannel | avg | 166ms | 170ms | 4ms | 2.41
| createGroupChannel | avg | 252ms | 256ms | 4ms | 1.59
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| login | p99 | 444ms | 10s | 9.556s | 2150.95
| createUser | p99 | 483ms | 898ms | 415ms | 85.87
| createSchedulePost | p99 | 5ms | 9ms | 4ms | 80.76
| getUsers | p99 | 52ms | 84ms | 32ms | 61.59
| saveReaction | p99 | 44ms | 68ms | 24ms | 54.07
| listCPAValues | p99 | 15ms | 22ms | 7ms | 48.08
| getUser | p99 | 62ms | 89ms | 27ms | 43.56
| getUsersByNames | p99 | 15ms | 21ms | 6ms | 39.54
| getChannelMembersForTeamForUser | p99 | 24ms | 33ms | 9ms | 37.32
| getChannelsForTeamForUser | p99 | 24ms | 31ms | 7ms | 29.72
| getTeamsUnreadForUser | p99 | 69ms | 86ms | 17ms | 24.79
| getThreadsForUser | p99 | 39ms | 48ms | 9ms | 22.97
| getCategoriesForTeamForUser | p99 | 71ms | 87ms | 16ms | 22.59
| getTeamScheduledPosts | p99 | 71ms | 86ms | 15ms | 21.09
| listChannelBookmarksForChannel | p99 | 20ms | 24ms | 4ms | 20.03
| getClientConfig | p99 | 79ms | 94ms | 15ms | 18.98
| getPostsForChannelAroundLastUnread | p99 | 191ms | 226ms | 35ms | 18.33
| getChannelMember | p99 | 80ms | 94ms | 14ms | 17.54
| listCPAFields | p99 | 42ms | 49ms | 7ms | 16.50
| getTeamsForUser | p99 | 40ms | 46ms | 6ms | 15.17
| getChannelsForUser | p99 | 40ms | 46ms | 6ms | 15.09
| viewChannel | p99 | 70ms | 80ms | 10ms | 14.38
| getTeamMembersForUser | p99 | 43ms | 49ms | 6ms | 13.93
| getChannelStats | p99 | 44ms | 50ms | 6ms | 13.54
| getChannelMembersForUser | p99 | 42ms | 47ms | 5ms | 12.02
| getAllTeams | p99 | 44ms | 49ms | 5ms | 11.32
| createPost | p99 | 816ms | 903ms | 87ms | 10.67
| getPostsForChannel | p99 | 189ms | 207ms | 18ms | 9.50
| upsertDraft | p99 | 22ms | 24ms | 2ms | 9.18
| searchUsers | p99 | 72ms | 76ms | 4ms | 5.58
| addChannelMember | p99 | 459ms | 482ms | 23ms | 5.01
| getPreferences | p99 | 45ms | 47ms | 2ms | 4.48
| createDirectChannel | p99 | 448ms | 459ms | 11ms | 2.46
| addTeamMember | p99 | 2.399s | 2.449s | 50ms | 2.08
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | avg | 2ms | 0s | -2ms | -106.73
| deleteChannelBookmark | avg | 14ms | 0s | -14ms | -102.64
| updateChannelBookmark | avg | 13ms | 0s | -13ms | -97.06
| createChannelBookmark | avg | 16ms | 12ms | -4ms | -24.92
| logout | avg | 27ms | 22ms | -5ms | -18.36
| createChannel | avg | 178ms | 156ms | -22ms | -12.34
| getProfileImage | avg | 95ms | 89ms | -6ms | -6.32
| getTeamStats | avg | 37ms | 35ms | -2ms | -5.44
| addChannelMember | avg | 171ms | 166ms | -5ms | -2.93
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| deleteChannelBookmark | p99 | 25ms | 0s | -25ms | -100.60
| getChannelUnread | p99 | 41ms | 5ms | -36ms | -88.89
| logout | p99 | 220ms | 48ms | -172ms | -78.18
| createChannelBookmark | p99 | 49ms | 25ms | -24ms | -49.10
| patchPost | p99 | 89ms | 50ms | -39ms | -43.91
| unfollowThreadByUser | p99 | 37ms | 25ms | -12ms | -32.69
| getTeamMember | p99 | 21ms | 17ms | -4ms | -18.76
| getDrafts | p99 | 23ms | 21ms | -2ms | -8.76
| getChannel | p99 | 41ms | 38ms | -3ms | -7.32
| getPostThread | p99 | 41ms | 39ms | -2ms | -4.92
| updateCategoriesForTeamForUser | p99 | 91ms | 87ms | -4ms | -4.40
| autocompleteUsers | p99 | 178ms | 172ms | -6ms | -3.37
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 5ms | 1ms | 24.470
| |  P99| 38ms| 45ms | 7ms | 18.567
| BotStore.Get |  Avg| 2ms| 4ms | 2ms | 90.775
| |  P99| 9ms| 22ms | 13ms | 142.077
| BotStore.GetAll |  Avg| 2ms| 0s | -2ms | -87.913
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.Delete |  Avg| 4ms| 0s | -4ms | -103.275
| |  P99| 10ms| 0s | -10ms | -102.040
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -98.723
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 3ms | 1ms | 41.651
| |  P99| 18ms| 22ms | 4ms | 22.668
| ChannelBookmarkStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 4ms | 1ms | 31.062
| |  P99| 24ms| 34ms | 10ms | 41.190
| ChannelStore.AnalyticsCountAll |  Avg| 15ms| 20ms | 5ms | 32.466
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 34ms | 1ms | 3.010
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 31ms| 30ms | -1ms | -3.183
| |  P99| 95ms| 94ms | -1ms | -1.049
| ChannelStore.CreateDirectChannel |  Avg| 17ms| 18ms | 1ms | 5.728
| |  P99| 86ms| 132ms | 46ms | 53.645
| ChannelStore.CreateInitialSidebarCategories |  Avg| 12ms| 16ms | 4ms | 34.061
| |  P99| 96ms| 178ms | 82ms | 85.586
| ChannelStore.CreateSidebarCategory |  Avg| 8ms| 11ms | 3ms | 39.839
| |  P99| 10ms| 25ms | 15ms | 150.754
| ChannelStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 37ms | 12ms | 48.513
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 37ms | 5ms | 15.644
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 11ms| 12ms | 1ms | 9.081
| |  P99| 77ms| 83ms | 6ms | 7.759
| ChannelStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.275
| ChannelStore.GetChannelUnread |  Avg| 3ms| 2ms | -1ms | -32.462
| |  P99| 41ms| 5ms | -36ms | -88.886
| ChannelStore.GetChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 30ms | 7ms | 29.807
| ChannelStore.GetChannelsByUser |  Avg| 4ms| 5ms | 1ms | 23.059
| |  P99| 39ms| 45ms | 6ms | 15.362
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 3ms | 1ms | 43.573
| |  P99| 16ms| 22ms | 6ms | 36.948
| ChannelStore.GetFileCount |  Avg| 2ms| 3ms | 1ms | 42.357
| |  P99| 16ms| 22ms | 6ms | 37.797
| ChannelStore.GetGuestCount |  Avg| 4ms| 6ms | 2ms | 44.593
| |  P99| 42ms| 48ms | 6ms | 14.181
| ChannelStore.GetMember |  Avg| 3ms| 4ms | 1ms | 36.310
| |  P99| 34ms| 44ms | 10ms | 29.211
| ChannelStore.GetMemberCount |  Avg| 18ms| 19ms | 1ms | 5.593
| |  P99| 78ms| 83ms | 5ms | 6.425
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 22ms | 4ms | 22.647
| ChannelStore.GetMemberLastViewedAt |  Avg| 3ms| 4ms | 1ms | 29.464
| |  P99| 37ms| 42ms | 5ms | 13.423
| ChannelStore.GetMembersForUser |  Avg| 3ms| 4ms | 1ms | 29.102
| |  P99| 24ms| 32ms | 8ms | 33.212
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| ChannelStore.GetMembersForUserWithPagination |  Avg| 5ms| 6ms | 1ms | 18.767
| |  P99| 41ms| 47ms | 6ms | 14.601
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 8ms | -2ms | -20.708
| ChannelStore.GetPublicChannelsForTeam |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 8ms| 10ms | 2ms | 25.094
| |  P99| 64ms| 81ms | 17ms | 26.511
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 7ms | 1ms | 15.939
| |  P99| 23ms| 38ms | 15ms | 64.378
| ChannelStore.GetTeamChannels |  Avg| 13ms| 12ms | -1ms | -7.669
| |  P99| 47ms| 25ms | -22ms | -46.316
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 32ms | 8ms | 33.138
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 0s | -2ms | -91.859
| |  P99| 19ms| 0s | -19ms | -101.211
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 42ms| 56ms | 14ms | 33.465
| ChannelStore.SaveMember |  Avg| 31ms| 36ms | 5ms | 16.209
| |  P99| 199ms| 227ms | 28ms | 14.106
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 28.911
| |  P99| 22ms| 23ms | 1ms | 4.544
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 39.870
| ChannelStore.UpdateSidebarCategories |  Avg| 19ms| 18ms | -1ms | -5.144
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 28ms | 10ms | 54.571
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 54.355
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 9ms | 6ms | 198.880
| |  P99| 9ms| 94ms | 85ms | 904.246
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 25.116
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 21ms | -2ms | -8.766
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 22ms | 3ms | 15.669
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 18ms | 8ms | 77.067
| EmojiStore.GetMultipleByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.Search |  Avg| 2ms| 0s | -2ms | -109.614
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 4ms| 5ms | 1ms | 22.700
| |  P99| 22ms| 28ms | 6ms | 27.198
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 32.952
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 23ms | 11ms | 94.415
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.351
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.788
| FileInfoStore.SetContent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 45ms| 61ms | 16ms | 35.604
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 3ms| 4ms | 1ms | 31.253
| |  P99| 31ms| 40ms | 9ms | 28.733
| GroupStore.GetByName |  Avg| 4ms| 5ms | 1ms | 26.019
| |  P99| 41ms| 47ms | 6ms | 14.761
| GroupStore.GetGroups |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 26ms | 3ms | 13.156
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 41ms | 16ms | 64.499
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 3ms| 2ms | -1ms | -38.743
| |  P99| 35ms| 21ms | -14ms | -39.716
| JobStore.GetNewestJobByStatusesAndType |  Avg| 3ms| 2ms | -1ms | -37.609
| |  P99| 25ms| 20ms | -5ms | -20.202
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 21ms | 12ms | 129.496
| JobStore.UpdateOptimistically |  Avg| 4ms| 3ms | -1ms | -25.297
| |  P99| 77ms| 30ms | -47ms | -61.047
| JobStore.UpdateStatus |  Avg| 4ms| 3ms | -1ms | -22.243
| |  P99| 78ms| 21ms | -57ms | -72.620
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 4ms | 1ms | 30.503
| |  P99| 19ms| 38ms | 19ms | 102.442
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.809
| LinkMetadataStore.Save |  Avg| 2ms| 4ms | 2ms | 81.844
| |  P99| 5ms| 41ms | 36ms | 727.273
| PluginStore.Delete |  Avg| 1ms| 0s | -1ms | -163.997
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 2ms| 4ms | 2ms | 107.962
| |  P99| 5ms| 82ms | 77ms | 1555.556
| PluginStore.SetWithOptions |  Avg| 2ms| 0s | -2ms | -80.071
| |  P99| 5ms| 0s | -5ms | -101.010
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 40.652
| |  P99| 26ms| 40ms | 14ms | 54.369
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 25ms | 3ms | 13.598
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 1ms | -1ms | -47.476
| |  P99| 23ms| 9ms | -14ms | -60.938
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 43ms | 20ms | 87.055
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 14ms | 5ms | 54.877
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 35ms | 8ms | 30.188
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 28ms | 5ms | 21.894
| PostStore.AnalyticsPostCount |  Avg| 132ms| 137ms | 5ms | 3.794
| |  P99| 495ms| 495ms | 0s | 0.000
| PostStore.AnalyticsPostCountByTeam |  Avg| 2ms| 1ms | -1ms | -45.349
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 10ms| 8ms | -2ms | -20.751
| |  P99| 25ms| 24ms | -1ms | -4.042
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 33ms | 8ms | 32.183
| PostStore.GetEtag |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 26ms| 37ms | 11ms | 42.366
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 3ms | 1ms | 51.000
| |  P99| 26ms| 40ms | 14ms | 53.868
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 21ms | 8ms | 61.843
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 3ms| 4ms | 1ms | 37.284
| |  P99| 9ms| 22ms | 13ms | 142.077
| PostStore.GetPosts |  Avg| 5ms| 6ms | 1ms | 20.648
| |  P99| 38ms| 45ms | 7ms | 18.382
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 9ms | -10ms | -51.811
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 24ms | 3ms | 14.478
| PostStore.GetPostsByThread |  Avg| 6ms| 5ms | -1ms | -17.732
| |  P99| 23ms| 23ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.630
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 9ms| 10ms | 1ms | 11.611
| |  P99| 55ms| 77ms | 22ms | 40.280
| PostStore.SearchPostsForUser |  Avg| 79ms| 80ms | 1ms | 1.270
| |  P99| 927ms| 928ms | 1ms | 0.108
| PostStore.SetPostReminder |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 10ms | 1ms | 10.654
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 4ms | 3ms | 325.501
| |  P99| 5ms| 47ms | 42ms | 848.485
| PreferenceStore.Get |  Avg| 2ms| 3ms | 1ms | 43.181
| |  P99| 18ms| 23ms | 5ms | 27.349
| PreferenceStore.GetAll |  Avg| 4ms| 5ms | 1ms | 22.246
| |  P99| 44ms| 46ms | 2ms | 4.573
| PreferenceStore.Save |  Avg| 8ms| 12ms | 4ms | 49.332
| |  P99| 83ms| 101ms | 18ms | 21.756
| ProductNoticesStore.ClearOldNotices |  Avg| 17ms| 15ms | -2ms | -12.070
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 24ms| 34ms | 10ms | 41.730
| |  P99| 217ms| 283ms | 66ms | 30.399
| PropertyFieldStore.SearchPropertyFields |  Avg| 4ms| 5ms | 1ms | 26.596
| |  P99| 39ms| 45ms | 6ms | 15.347
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 41.209
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 31.131
| |  P99| 10ms| 30ms | 20ms | 206.554
| RetentionPolicyStore.GetAll |  Avg| 2ms| 0s | -2ms | -123.903
| |  P99| 5ms| 0s | -5ms | -101.010
| RetentionPolicyStore.GetCount |  Avg| 1ms| 0s | -1ms | -105.374
| |  P99| 5ms| 0s | -5ms | -101.010
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -76.257
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 2ms| 3ms | 1ms | 41.210
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 4ms| 5ms | 1ms | 26.603
| |  P99| 39ms| 45ms | 6ms | 15.525
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| SchemeStore.GetAllPage |  Avg| 2ms| 0s | -2ms | -131.077
| |  P99| 5ms| 0s | -5ms | -101.010
| SessionStore.Get |  Avg| 7ms| 9ms | 2ms | 30.654
| |  P99| 69ms| 85ms | 16ms | 23.134
| SessionStore.GetLRUSessions |  Avg| 4ms| 5ms | 1ms | 27.982
| |  P99| 37ms| 44ms | 7ms | 19.097
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 2ms | -1ms | -31.339
| |  P99| 22ms| 9ms | -13ms | -59.090
| SessionStore.Save |  Avg| 7ms| 9ms | 2ms | 27.174
| |  P99| 52ms| 77ms | 25ms | 48.307
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 72.644
| SharedChannelStore.HasChannel |  Avg| 2ms| 0s | -2ms | -98.810
| |  P99| 16ms| 0s | -16ms | -102.470
| StatusStore.Get |  Avg| 3ms| 4ms | 1ms | 30.068
| |  P99| 35ms| 42ms | 7ms | 20.204
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.235
| StatusStore.SaveOrUpdate |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 35ms | 7ms | 25.197
| StatusStore.SaveOrUpdateMany |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 40ms| 25ms | -15ms | -37.272
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 55ms| 28ms | -27ms | -48.649
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 69.344
| SystemStore.GetByName |  Avg| 2ms| 3ms | 1ms | 55.066
| |  P99| 31ms| 41ms | 10ms | 32.564
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 0s | -2ms | -93.967
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.SaveOrUpdate |  Avg| 2ms| 0s | -2ms | -84.588
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 67.387
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 35ms | -1ms | -2.742
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 4ms| 5ms | 1ms | 26.775
| |  P99| 40ms| 46ms | 6ms | 15.151
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 4ms| 5ms | 1ms | 25.472
| |  P99| 39ms| 45ms | 6ms | 15.468
| TeamStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 33ms| 40ms | 7ms | 21.408
| TeamStore.GetTeamsByUserId |  Avg| 4ms| 5ms | 1ms | 26.169
| |  P99| 39ms| 46ms | 7ms | 17.942
| TeamStore.GetTeamsForUser |  Avg| 4ms| 5ms | 1ms | 25.307
| |  P99| 40ms| 46ms | 6ms | 15.111
| TeamStore.GetTotalMemberCount |  Avg| 37ms| 35ms | -2ms | -5.459
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 24ms| 23ms | -1ms | -4.154
| |  P99| 98ms| 96ms | -2ms | -2.032
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.928
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 19ms | 6ms | 47.672
| ThreadStore.GetTeamsUnreadForUser |  Avg| 5ms| 6ms | 1ms | 21.645
| |  P99| 43ms| 51ms | 8ms | 18.609
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 20ms | 3ms | 17.148
| ThreadStore.GetThreadForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 32ms | 7ms | 28.361
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 24ms | 4ms | 19.854
| ThreadStore.GetTotalThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 43ms | 9ms | 26.542
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 4ms | 1ms | 29.802
| |  P99| 31ms| 40ms | 9ms | 28.611
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 34ms| 43ms | 9ms | 26.108
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 35ms| 43ms | 8ms | 23.136
| ThreadStore.MaintainMembership |  Avg| 3ms| 4ms | 1ms | 29.802
| |  P99| 19ms| 34ms | 15ms | 80.070
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.219
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 30.912
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 4ms | 2ms | 101.289
| |  P99| 9ms| 24ms | 15ms | 162.089
| UserStore.AnalyticsActiveCount |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 195ms| 191ms | -4ms | -2.050
| UserStore.Count |  Avg| 14ms| 15ms | 1ms | 7.209
| |  P99| 65ms| 72ms | 7ms | 10.770
| UserStore.Get |  Avg| 2ms| 3ms | 1ms | 47.168
| |  P99| 23ms| 33ms | 10ms | 43.046
| UserStore.GetAllProfiles |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 34ms | 8ms | 30.985
| UserStore.GetAllProfilesInChannel |  Avg| 172ms| 185ms | 13ms | 7.539
| |  P99| 492ms| 509ms | 17ms | 3.454
| UserStore.GetByUsername |  Avg| 2ms| 3ms | 1ms | 44.690
| |  P99| 15ms| 33ms | 18ms | 123.509
| UserStore.GetForLogin |  Avg| 4ms| 5ms | 1ms | 24.503
| |  P99| 41ms| 47ms | 6ms | 14.732
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 19ms | 14ms | 282.733
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 35ms | 10ms | 39.679
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 21ms | 6ms | 40.565
| UserStore.GetProfilesInChannel |  Avg| 20ms| 28ms | 8ms | 39.942
| |  P99| 234ms| 241ms | 7ms | 2.998
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 19.775
| UserStore.IsEmpty |  Avg| 2ms| 3ms | 1ms | 50.228
| |  P99| 23ms| 24ms | 1ms | 4.379
| UserStore.Save |  Avg| 77ms| 150ms | 73ms | 95.229
| |  P99| 234ms| 454ms | 220ms | 94.011
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 67ms| 72ms | 5ms | 7.470
| UserStore.Update |  Avg| 5ms| 8ms | 3ms | 55.355
| |  P99| 21ms| 84ms | 63ms | 297.519
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 45ms | 2ms | 4.612
| UserStore.UpdateLastLogin |  Avg| 5ms| 6ms | 1ms | 21.280
| |  P99| 32ms| 42ms | 10ms | 30.981
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 38ms | 8ms | 26.722
| UserTermsOfServiceStore.GetByUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 38ms| 45ms | 7ms | 18.547
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 5ms | 1ms | 22.481
| |  P99| 32ms| 36ms | 4ms | 12.444
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 171ms| 166ms | -5ms | -2.930
| | P99| 459ms| 482ms | 23ms | 5.009
| addTeamMember | Avg| 685ms| 773ms | 88ms | 12.841
| | P99| 2.399s| 2.449s | 50ms | 2.084
| autocompleteChannelsForTeamForSearch | Avg| 31ms| 30ms | -1ms | -3.177
| | P99| 95ms| 94ms | -1ms | -1.049
| autocompleteEmojis | Avg| 2ms| 0s | -2ms | -106.728
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 178ms| 172ms | -6ms | -3.368
| createCategoryForTeamForUser | Avg| 11ms| 17ms | 6ms | 53.889
| | P99| 25ms| 25ms | 0s | 0.000
| createChannel | Avg| 178ms| 156ms | -22ms | -12.342
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 16ms| 12ms | -4ms | -24.918
| | P99| 49ms| 25ms | -24ms | -49.105
| createDirectChannel | Avg| 166ms| 170ms | 4ms | 2.412
| | P99| 448ms| 459ms | 11ms | 2.456
| createGroupChannel | Avg| 252ms| 256ms | 4ms | 1.589
| | P99| 496ms| 495ms | -1ms | -0.202
| createPost | Avg| 153ms| 162ms | 9ms | 5.872
| | P99| 816ms| 903ms | 87ms | 10.665
| createSchedulePost | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.763
| createUser | Avg| 152ms| 243ms | 91ms | 59.945
| | P99| 483ms| 898ms | 415ms | 85.872
| deleteChannelBookmark | Avg| 14ms| 0s | -14ms | -102.635
| | P99| 25ms| 0s | -25ms | -100.604
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.730
| deletePost | Avg| 15ms| 14ms | -1ms | -6.789
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.082
| getAllTeams | Avg| 4ms| 5ms | 1ms | 23.206
| | P99| 44ms| 49ms | 5ms | 11.318
| getAnalytics | Avg| 30ms| 44ms | 14ms | 46.812
| | P99| 50ms| 50ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 9ms| 10ms | 1ms | 11.745
| | P99| 71ms| 87ms | 16ms | 22.588
| getChannel | Avg| 6ms| 7ms | 1ms | 18.180
| | P99| 41ms| 38ms | -3ms | -7.317
| getChannelMember | Avg| 8ms| 10ms | 2ms | 25.233
| | P99| 80ms| 94ms | 14ms | 17.542
| getChannelMembersForTeamForUser | Avg| 3ms| 4ms | 1ms | 28.636
| | P99| 24ms| 33ms | 9ms | 37.321
| getChannelMembersForUser | Avg| 5ms| 6ms | 1ms | 18.406
| | P99| 42ms| 47ms | 5ms | 12.021
| getChannelStats | Avg| 2ms| 3ms | 1ms | 43.128
| | P99| 44ms| 50ms | 6ms | 13.536
| getChannelUnread | Avg| 3ms| 2ms | -1ms | -30.608
| | P99| 41ms| 5ms | -36ms | -88.886
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 31ms | 7ms | 29.721
| getChannelsForUser | Avg| 4ms| 6ms | 2ms | 44.696
| | P99| 40ms| 46ms | 6ms | 15.090
| getClientConfig | Avg| 6ms| 8ms | 2ms | 35.275
| | P99| 79ms| 94ms | 15ms | 18.980
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 23ms| 21ms | -2ms | -8.762
| getFilePreview | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 96ms| 97ms | 1ms | 1.037
| getFileThumbnail | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 93ms| 94ms | 1ms | 1.073
| getFilteredUsersStats | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getPostThread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 41ms| 39ms | -2ms | -4.916
| getPostsForChannel | Avg| 20ms| 22ms | 2ms | 9.772
| | P99| 189ms| 207ms | 18ms | 9.502
| getPostsForChannelAroundLastUnread | Avg| 21ms| 27ms | 6ms | 28.083
| | P99| 191ms| 226ms | 35ms | 18.328
| getPreferences | Avg| 5ms| 6ms | 1ms | 21.578
| | P99| 45ms| 47ms | 2ms | 4.484
| getPrevTrialLicense | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 95ms| 89ms | -6ms | -6.323
| | P99| 459ms| 458ms | -1ms | -0.218
| getPublicChannelsForTeam | Avg| 15ms| 14ms | -1ms | -6.889
| | P99| 48ms| 48ms | 0s | 0.000
| getRolesByNames | Avg| 2ms| 1ms | -1ms | -64.732
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 21ms| 17ms | -4ms | -18.758
| getTeamMembersForUser | Avg| 4ms| 5ms | 1ms | 22.891
| | P99| 43ms| 49ms | 6ms | 13.933
| getTeamScheduledPosts | Avg| 8ms| 10ms | 2ms | 25.836
| | P99| 71ms| 86ms | 15ms | 21.091
| getTeamStats | Avg| 37ms| 35ms | -2ms | -5.437
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 4ms| 5ms | 1ms | 25.565
| | P99| 40ms| 46ms | 6ms | 15.172
| getTeamsUnreadForUser | Avg| 7ms| 9ms | 2ms | 27.948
| | P99| 69ms| 86ms | 17ms | 24.791
| getThreadsForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 39ms| 48ms | 9ms | 22.974
| getUser | Avg| 5ms| 7ms | 2ms | 40.509
| | P99| 62ms| 89ms | 27ms | 43.561
| getUserByUsername | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 5ms| 7ms | 2ms | 40.565
| | P99| 52ms| 84ms | 32ms | 61.586
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.008
| getUsersByNames | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 21ms | 6ms | 39.541
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 4ms| 5ms | 1ms | 24.007
| | P99| 42ms| 49ms | 7ms | 16.498
| listCPAValues | Avg| 2ms| 3ms | 1ms | 44.969
| | P99| 15ms| 22ms | 7ms | 48.077
| listChannelBookmarksForChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 24ms | 4ms | 20.033
| login | Avg| 74ms| 864ms | 790ms | 1065.783
| | P99| 444ms| 10s | 9.556s | 2150.954
| logout | Avg| 27ms| 22ms | -5ms | -18.357
| | P99| 220ms| 48ms | -172ms | -78.181
| patchPost | Avg| 23ms| 22ms | -1ms | -4.409
| | P99| 89ms| 50ms | -39ms | -43.911
| removeUserCustomStatus | Avg| 116ms| 122ms | 6ms | 5.179
| | P99| 248ms| 247ms | -1ms | -0.404
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 10ms | 1ms | 10.627
| | P99| 44ms| 68ms | 24ms | 54.071
| searchAllChannels | Avg| 33ms| 34ms | 1ms | 2.988
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.544
| searchPostsInTeam | Avg| 86ms| 89ms | 3ms | 3.487
| | P99| 927ms| 933ms | 6ms | 0.647
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 72ms| 76ms | 4ms | 5.582
| setPostReminder | Avg| 15ms| 16ms | 1ms | 6.875
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 9ms | -1ms | -10.183
| | P99| 37ms| 25ms | -12ms | -32.694
| updateCategoriesForTeamForUser | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 91ms| 87ms | -4ms | -4.396
| updateChannelBookmark | Avg| 13ms| 0s | -13ms | -97.058
| | P99| 25ms| 0s | -25ms | -100.604
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.369
| updateReadStateAllThreadsByUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 37ms| 36ms | -1ms | -2.714
| | P99| 97ms| 96ms | -1ms | -1.036
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 410ms| 413ms | 3ms | 0.732
| | P99| 990ms| 990ms | 0s | 0.000
| upsertDraft | Avg| 3ms| 4ms | 1ms | 30.003
| | P99| 22ms| 24ms | 2ms | 9.177
| viewChannel | Avg| 11ms| 10ms | -1ms | -9.051
| | P99| 70ms| 80ms | 10ms | 14.379
