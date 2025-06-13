### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 12ms | 31ms | 19ms | 153.57
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPriorityStore.GetForPost | p99 | 9ms | 22ms | 13ms | 146.40
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 96ms | 219ms | 123ms | 128.68
| UserStore.AutocompleteUsersInChannel | p99 | 139ms | 222ms | 83ms | 59.62
| PostStore.GetPosts | p99 | 15ms | 22ms | 7ms | 45.90
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 0s | -4ms | -112.75
| ScheduledPostStore.GetPendingScheduledPosts | avg | 4ms | 0s | -4ms | -112.30
| EmojiStore.GetMultipleByName | avg | 2ms | 0s | -2ms | -112.02
| RoleStore.GetByNames | avg | 3ms | 0s | -3ms | -107.96
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 7ms | 0s | -7ms | -106.34
| SessionStore.Remove | avg | 3ms | 0s | -3ms | -104.22
| ChannelStore.GetTeamChannels | avg | 14ms | 0s | -14ms | -103.64
| PostStore.GetPostReminderMetadata | avg | 3ms | 0s | -3ms | -103.05
| ChannelBookmarkStore.Delete | avg | 5ms | 0s | -5ms | -102.99
| SharedChannelStore.HasChannel | avg | 2ms | 0s | -2ms | -102.92
| UserAccessTokenStore.GetByToken | avg | 2ms | 0s | -2ms | -102.62
| PostStore.Delete | avg | 15ms | 0s | -15ms | -101.98
| TokenStore.Cleanup | avg | 2ms | 0s | -2ms | -101.12
| TeamStore.GetTotalMemberCount | avg | 37ms | 0s | -37ms | -100.93
| TeamStore.GetActiveMemberCount | avg | 37ms | 0s | -37ms | -100.74
| CommandWebhookStore.Cleanup | avg | 2ms | 0s | -2ms | -100.55
| PostStore.AnalyticsPostCount | avg | 259ms | 0s | -259ms | -99.97
| ChannelStore.UpdateSidebarCategories | avg | 38ms | 0s | -38ms | -99.57
| ChannelStore.CreateSidebarCategory | avg | 43ms | 0s | -43ms | -99.50
| UserStore.GetProfilesInChannel | avg | 20ms | 0s | -20ms | -99.28
| ProductNoticesStore.ClearOldNotices | avg | 14ms | 0s | -14ms | -97.98
| ChannelStore.GetSidebarCategory | avg | 8ms | 0s | -8ms | -97.19
| ChannelStore.GetMembers | avg | 8ms | 0s | -8ms | -97.05
| ScheduledPostStore.CreateScheduledPost | avg | 3ms | 0s | -3ms | -96.87
| ChannelStore.IsReadOnlyChannel | avg | 2ms | 0s | -2ms | -96.41
| ChannelBookmarkStore.Save | avg | 8ms | 0s | -8ms | -95.69
| UserStore.GetMany | avg | 2ms | 0s | -2ms | -95.48
| UserStore.GetProfilesNotInChannel | avg | 4ms | 0s | -4ms | -94.67
| PreferenceStore.DeleteCategoryAndName | avg | 3ms | 0s | -3ms | -93.48
| PostStore.SetPostReminder | avg | 6ms | 0s | -6ms | -93.32
| ScheduledPostStore.GetScheduledPostsForUser | avg | 2ms | 0s | -2ms | -90.31
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -88.92
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 2ms | 0s | -2ms | -88.70
| StatusStore.SaveOrUpdate | avg | 16ms | 3ms | -13ms | -83.56
| WebhookStore.GetOutgoingByTeam | avg | 5ms | 2ms | -3ms | -61.02
| ThreadStore.GetThreadUnreadReplyCount | avg | 6ms | 3ms | -3ms | -51.86
| ChannelStore.AutocompleteInTeamForSearch | avg | 46ms | 23ms | -23ms | -49.47
| ChannelStore.GetByName | avg | 4ms | 2ms | -2ms | -44.65
| PostStore.SearchPostsForUser | avg | 40ms | 24ms | -16ms | -39.75
| PostStore.GetPostsByThread | avg | 5ms | 3ms | -2ms | -39.20
| PostStore.GetPostsSince | avg | 8ms | 5ms | -3ms | -36.01
| ThreadStore.GetThreadForUser | avg | 6ms | 4ms | -2ms | -35.68
| ChannelStore.GetMemberCount | avg | 15ms | 11ms | -4ms | -25.85
| UserStore.GetAllProfilesInChannel | avg | 155ms | 119ms | -36ms | -23.24
| ProductNoticesStore.View | avg | 32ms | 25ms | -7ms | -22.02
| UserStore.Count | avg | 10ms | 8ms | -2ms | -19.91
| ChannelStore.Save | avg | 11ms | 9ms | -2ms | -18.33
| PostStore.Save | avg | 11ms | 9ms | -2ms | -18.00
| TeamStore.SaveMember | avg | 24ms | 21ms | -3ms | -12.64
| ChannelStore.SaveMember | avg | 27ms | 24ms | -3ms | -11.27
| UserStore.AutocompleteUsersInChannel | avg | 38ms | 34ms | -4ms | -10.64
| ChannelStore.Autocomplete | avg | 33ms | 30ms | -3ms | -9.04
| UserStore.Save | avg | 69ms | 66ms | -3ms | -4.34
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.CreateScheduledPost | p99 | 8ms | 0s | -8ms | -106.67
| ChannelStore.IsReadOnlyChannel | p99 | 10ms | 0s | -10ms | -104.53
| UserStore.GetMany | p99 | 7ms | 0s | -7ms | -103.70
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 10ms | 0s | -10ms | -101.69
| PostStore.GetPostReminderMetadata | p99 | 19ms | 0s | -19ms | -101.60
| ChannelStore.GetMembers | p99 | 25ms | 0s | -25ms | -101.21
| PreferenceStore.DeleteCategoryAndName | p99 | 23ms | 0s | -23ms | -101.10
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -101.01
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 0s | -5ms | -101.01
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -101.01
| EmojiStore.GetMultipleByName | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| TokenStore.Cleanup | p99 | 5ms | 0s | -5ms | -101.00
| CommandWebhookStore.Cleanup | p99 | 5ms | 0s | -5ms | -101.00
| SessionStore.Remove | p99 | 5ms | 0s | -5ms | -101.00
| UserStore.GetProfilesNotInChannel | p99 | 5ms | 0s | -5ms | -101.00
| UserAccessTokenStore.GetByToken | p99 | 5ms | 0s | -5ms | -100.99
| ScheduledPostStore.GetMaxMessageSize | p99 | 5ms | 0s | -5ms | -100.99
| PostStore.SetPostReminder | p99 | 22ms | 0s | -22ms | -100.69
| PostStore.Delete | p99 | 25ms | 0s | -25ms | -100.60
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 0s | -25ms | -100.60
| ChannelStore.GetTeamChannels | p99 | 46ms | 0s | -46ms | -100.53
| ChannelStore.CreateSidebarCategory | p99 | 99ms | 0s | -99ms | -100.51
| TeamStore.GetActiveMemberCount | p99 | 50ms | 0s | -50ms | -100.50
| TeamStore.GetTotalMemberCount | p99 | 50ms | 0s | -50ms | -100.50
| UserStore.GetProfilesInChannel | p99 | 236ms | 0s | -236ms | -100.11
| PostStore.AnalyticsPostCount | p99 | 498ms | 0s | -498ms | -100.10
| ChannelStore.UpdateSidebarCategories | p99 | 92ms | 0s | -92ms | -100.00
| ChannelStore.GetSidebarCategory | p99 | 68ms | 0s | -68ms | -100.00
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 46ms | 0s | -46ms | -99.46
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 42ms | 0s | -42ms | -99.41
| ChannelBookmarkStore.Save | p99 | 24ms | 0s | -24ms | -99.38
| SharedChannelStore.HasChannel | p99 | 8ms | 0s | -8ms | -98.83
| StatusStore.SaveOrUpdate | p99 | 376ms | 5ms | -371ms | -98.60
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 8ms | 0s | -8ms | -94.67
| BotStore.Get | p99 | 42ms | 5ms | -37ms | -87.57
| WebhookStore.GetOutgoingByTeam | p99 | 38ms | 5ms | -33ms | -86.30
| RoleStore.GetByNames | p99 | 37ms | 5ms | -32ms | -85.33
| PostStore.SearchPostsForUser | p99 | 1.336s | 223ms | -1.113s | -83.28
| ChannelStore.GetByName | p99 | 35ms | 7ms | -28ms | -79.78
| ChannelStore.Save | p99 | 45ms | 10ms | -35ms | -77.67
| ChannelStore.SearchGroupChannels | p99 | 22ms | 5ms | -17ms | -76.01
| DraftStore.GetDraftsForUser | p99 | 19ms | 5ms | -14ms | -75.31
| JobStore.GetAllByStatus | p99 | 19ms | 5ms | -14ms | -74.75
| ThreadStore.GetThreadsForUser | p99 | 19ms | 5ms | -14ms | -74.70
| JobStore.UpdateStatus | p99 | 19ms | 5ms | -14ms | -74.57
| FileInfoStore.Save | p99 | 23ms | 6ms | -17ms | -74.15
| LinkMetadataStore.Save | p99 | 19ms | 5ms | -14ms | -73.68
| DraftStore.Upsert | p99 | 18ms | 5ms | -13ms | -72.30
| ChannelStore.GetMember | p99 | 18ms | 5ms | -13ms | -71.92
| PostStore.GetEtag | p99 | 18ms | 5ms | -13ms | -71.88
| ChannelStore.GetMembersForUserWithPagination | p99 | 16ms | 5ms | -11ms | -70.37
| PreferenceStore.GetAll | p99 | 17ms | 5ms | -12ms | -70.26
| PluginStore.List | p99 | 16ms | 5ms | -11ms | -70.06
| ChannelStore.GetChannels | p99 | 16ms | 5ms | -11ms | -69.76
| ThreadStore.GetThreadUnreadReplyCount | p99 | 24ms | 7ms | -17ms | -69.43
| PostPersistentNotificationStore.Get | p99 | 17ms | 5ms | -12ms | -69.16
| ChannelStore.GetGuestCount | p99 | 17ms | 5ms | -12ms | -68.95
| DraftStore.Delete | p99 | 15ms | 5ms | -10ms | -68.07
| ThreadStore.GetTotalUnreadMentions | p99 | 16ms | 5ms | -11ms | -67.51
| UserStore.GetProfileByIds | p99 | 15ms | 5ms | -10ms | -66.74
| ChannelStore.GetMembersForUser | p99 | 15ms | 5ms | -10ms | -66.62
| DraftStore.Get | p99 | 15ms | 5ms | -10ms | -66.59
| FileInfoStore.SetContent | p99 | 29ms | 10ms | -19ms | -66.38
| UserStore.UpdateFailedPasswordAttempts | p99 | 21ms | 7ms | -14ms | -65.97
| PreferenceStore.Get | p99 | 14ms | 5ms | -9ms | -64.53
| GroupStore.GetByName | p99 | 14ms | 5ms | -9ms | -64.35
| PostStore.GetPostsByThread | p99 | 23ms | 8ms | -15ms | -64.19
| ProductNoticesStore.View | p99 | 138ms | 50ms | -88ms | -63.99
| JobStore.UpdateOptimistically | p99 | 13ms | 5ms | -8ms | -63.75
| ChannelStore.Get | p99 | 14ms | 5ms | -9ms | -63.39
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 13ms | 5ms | -8ms | -61.73
| ChannelStore.IncrementMentionCount | p99 | 13ms | 5ms | -8ms | -61.68
| ThreadStore.GetThreadForUser | p99 | 25ms | 10ms | -15ms | -61.14
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 13ms | 5ms | -8ms | -60.90
| ThreadStore.GetTeamsUnreadForUser | p99 | 13ms | 5ms | -8ms | -60.80
| UserStore.Count | p99 | 25ms | 10ms | -15ms | -60.54
| TeamStore.GetTeamsForUser | p99 | 12ms | 5ms | -7ms | -59.58
| UserStore.GetProfilesByUsernames | p99 | 12ms | 5ms | -7ms | -59.57
| ChannelStore.UpdateLastViewedAt | p99 | 12ms | 5ms | -7ms | -59.43
| SessionStore.Get | p99 | 24ms | 10ms | -14ms | -57.63
| PostAcknowledgementStore.GetForPosts | p99 | 21ms | 9ms | -12ms | -57.60
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 12ms | 5ms | -7ms | -57.21
| UserStore.GetAllProfiles | p99 | 11ms | 5ms | -6ms | -56.68
| PostPriorityStore.GetForPosts | p99 | 21ms | 9ms | -12ms | -56.41
| GroupStore.GetGroups | p99 | 12ms | 5ms | -7ms | -56.03
| PostStore.Get | p99 | 23ms | 10ms | -13ms | -55.98
| PostStore.GetPostReminders | p99 | 23ms | 10ms | -13ms | -55.44
| TeamStore.GetAllPage | p99 | 11ms | 5ms | -6ms | -54.39
| ThreadStore.GetTotalUnreadThreads | p99 | 11ms | 5ms | -6ms | -54.37
| ThreadStore.GetTotalThreads | p99 | 11ms | 5ms | -6ms | -53.60
| ThreadStore.MaintainMembership | p99 | 22ms | 10ms | -12ms | -53.45
| TeamStore.GetMember | p99 | 11ms | 5ms | -6ms | -53.36
| UserStore.GetForLogin | p99 | 11ms | 5ms | -6ms | -53.22
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 11ms | 5ms | -6ms | -53.05
| UserStore.Get | p99 | 10ms | 5ms | -5ms | -52.50
| ThreadStore.UpdateMembership | p99 | 10ms | 5ms | -5ms | -52.46
| ThreadStore.GetThreadFollowers | p99 | 10ms | 5ms | -5ms | -52.25
| UserStore.GetByUsername | p99 | 10ms | 5ms | -5ms | -52.16
| ThreadStore.GetMembershipForUser | p99 | 10ms | 5ms | -5ms | -52.15
| PostAcknowledgementStore.GetForPost | p99 | 10ms | 5ms | -5ms | -52.08
| UserStore.GetUnreadCount | p99 | 19ms | 9ms | -10ms | -52.00
| FileInfoStore.AttachToPost | p99 | 21ms | 10ms | -11ms | -51.90
| ChannelStore.GetChannelsByUser | p99 | 10ms | 5ms | -5ms | -51.85
| SessionStore.GetLRUSessions | p99 | 10ms | 5ms | -5ms | -51.57
| ChannelStore.GetMemberForPost | p99 | 21ms | 10ms | -11ms | -51.26
| ThreadStore.MarkAsRead | p99 | 10ms | 5ms | -5ms | -51.09
| SessionStore.UpdateLastActivityAt | p99 | 10ms | 5ms | -5ms | -50.70
| StatusStore.Get | p99 | 10ms | 5ms | -5ms | -50.68
| ChannelStore.GetMemberLastViewedAt | p99 | 10ms | 5ms | -5ms | -50.49
| StatusStore.UpdateLastActivityAt | p99 | 10ms | 5ms | -5ms | -50.35
| FileInfoStore.Get | p99 | 10ms | 5ms | -5ms | -50.13
| PluginStore.SetWithOptions | p99 | 20ms | 10ms | -10ms | -49.60
| SessionStore.Save | p99 | 22ms | 11ms | -11ms | -49.32
| StatusStore.UpdateExpiredDNDStatuses | p99 | 20ms | 10ms | -10ms | -49.14
| UserTermsOfServiceStore.GetByUser | p99 | 10ms | 5ms | -5ms | -48.95
| PostStore.GetPostsSince | p99 | 47ms | 24ms | -23ms | -48.92
| ClusterDiscoveryStore.SetLastPingAt | p99 | 25ms | 13ms | -12ms | -48.50
| TeamStore.GetTeamsByUserId | p99 | 10ms | 5ms | -5ms | -48.36
| UserStore.GetAllProfilesInChannel | p99 | 474ms | 248ms | -226ms | -47.63
| StatusStore.GetByIds | p99 | 17ms | 9ms | -8ms | -46.76
| PostStore.GetSingle | p99 | 9ms | 5ms | -4ms | -46.35
| ChannelStore.GetChannelUnread | p99 | 9ms | 5ms | -4ms | -45.54
| PluginStore.Delete | p99 | 9ms | 5ms | -4ms | -45.29
| PostStore.GetPostsBefore | p99 | 18ms | 10ms | -8ms | -45.12
| PostStore.GetPostIdAfterTime | p99 | 9ms | 5ms | -4ms | -44.81
| SystemStore.GetByName | p99 | 9ms | 5ms | -4ms | -44.58
| PostStore.GetPostIdBeforeTime | p99 | 9ms | 5ms | -4ms | -44.39
| ChannelStore.GetMemberCount | p99 | 45ms | 25ms | -20ms | -44.35
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 5ms | -4ms | -44.31
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 9ms | 5ms | -4ms | -44.29
| UserStore.UpdateUpdateAt | p99 | 18ms | 10ms | -8ms | -43.91
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 9ms | 5ms | -4ms | -43.84
| LinkMetadataStore.Get | p99 | 9ms | 5ms | -4ms | -43.71
| FileInfoStore.GetByIds | p99 | 9ms | 5ms | -4ms | -43.38
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -42.95
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 9ms | 5ms | -4ms | -42.93
| UserStore.Save | p99 | 175ms | 100ms | -75ms | -42.81
| FileInfoStore.GetForPost | p99 | 9ms | 5ms | -4ms | -42.77
| ChannelStore.GetFileCount | p99 | 9ms | 5ms | -4ms | -42.34
| UserStore.UpdateLastLogin | p99 | 17ms | 10ms | -7ms | -41.40
| ChannelStore.SaveMember | p99 | 81ms | 49ms | -32ms | -39.37
| UserStore.Update | p99 | 16ms | 10ms | -6ms | -38.40
| PostPersistentNotificationStore.GetSingle | p99 | 8ms | 5ms | -3ms | -38.23
| JobStore.GetCountByStatusAndType | p99 | 8ms | 5ms | -3ms | -38.10
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 8ms | 5ms | -3ms | -37.96
| JobStore.Save | p99 | 8ms | 5ms | -3ms | -37.85
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 40ms | 25ms | -15ms | -37.15
| TeamStore.Get | p99 | 8ms | 5ms | -3ms | -36.99
| EmojiStore.GetByName | p99 | 8ms | 5ms | -3ms | -35.56
| ThreadStore.MarkAllAsReadByChannels | p99 | 8ms | 5ms | -3ms | -35.30
| ChannelStore.GetPublicChannelsForTeam | p99 | 37ms | 25ms | -12ms | -32.12
| PreferenceStore.Save | p99 | 35ms | 24ms | -11ms | -31.29
| ReactionStore.GetForPost | p99 | 14ms | 10ms | -4ms | -29.32
| UserStore.Search | p99 | 69ms | 49ms | -20ms | -29.01
| PostStore.Save | p99 | 47ms | 34ms | -13ms | -27.51
| JobStore.UpdateStatusOptimistically | p99 | 29ms | 22ms | -7ms | -23.93
| TeamStore.SaveMember | p99 | 56ms | 44ms | -12ms | -21.29
| ChannelStore.CreateDirectChannel | p99 | 62ms | 49ms | -13ms | -21.14
| AuditStore.Save | p99 | 20ms | 16ms | -4ms | -20.27
| ChannelStore.GetAllChannelMembersForUser | p99 | 29ms | 24ms | -5ms | -17.09
| ChannelStore.CreateInitialSidebarCategories | p99 | 50ms | 45ms | -5ms | -10.09
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createPost | avg | 203ms | 429ms | 226ms | 111.41
| getChannelStats | avg | 2ms | 4ms | 2ms | 94.63
| getChannel | avg | 5ms | 9ms | 4ms | 78.20
| getProfileImage | avg | 66ms | 104ms | 38ms | 57.99
| uploadFileStream | avg | 401ms | 481ms | 80ms | 19.95
| login | avg | 66ms | 69ms | 3ms | 4.57
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteUsers | p99 | 108ms | 217ms | 109ms | 100.69
| getProfileImage | p99 | 249ms | 470ms | 221ms | 88.61
| login | p99 | 243ms | 246ms | 3ms | 1.24
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 4ms | 0s | -4ms | -110.52
| getTeamScheduledPosts | avg | 5ms | 0s | -5ms | -109.28
| getChannelMembers | avg | 9ms | 0s | -9ms | -103.51
| setPostReminder | avg | 20ms | 0s | -20ms | -102.05
| followThreadByUser | avg | 13ms | 0s | -13ms | -101.88
| deletePost | avg | 23ms | 0s | -23ms | -101.47
| updateChannelBookmark | avg | 26ms | 0s | -26ms | -100.57
| getTeamStats | avg | 37ms | 0s | -37ms | -100.20
| createChannel | avg | 191ms | 0s | -191ms | -99.81
| createCategoryForTeamForUser | avg | 45ms | 0s | -45ms | -99.76
| updateCategoriesForTeamForUser | avg | 57ms | 0s | -57ms | -99.54
| logout | avg | 30ms | 0s | -30ms | -98.63
| createChannelBookmark | avg | 22ms | 0s | -22ms | -98.32
| unfollowThreadByUser | avg | 13ms | 0s | -13ms | -97.85
| createSchedulePost | avg | 3ms | 0s | -3ms | -85.98
| removeUserCustomStatus | avg | 138ms | 33ms | -105ms | -76.23
| getUsers | avg | 3ms | 1ms | -2ms | -63.60
| getThreadsForUser | avg | 4ms | 2ms | -2ms | -54.64
| getPostsForChannel | avg | 23ms | 11ms | -12ms | -52.21
| autocompleteChannelsForTeamForSearch | avg | 47ms | 23ms | -24ms | -51.56
| createDirectChannel | avg | 200ms | 106ms | -94ms | -47.04
| createGroupChannel | avg | 306ms | 167ms | -139ms | -45.42
| addChannelMember | avg | 179ms | 105ms | -74ms | -41.33
| viewChannel | avg | 12ms | 8ms | -4ms | -34.62
| createUser | avg | 142ms | 99ms | -43ms | -30.35
| searchPostsInTeam | avg | 47ms | 36ms | -11ms | -23.37
| updateReadStateThreadByUser | avg | 37ms | 29ms | -8ms | -21.36
| getCategoriesForTeamForUser | avg | 14ms | 12ms | -2ms | -14.72
| addTeamMember | avg | 552ms | 477ms | -75ms | -13.59
| searchAllChannels | avg | 33ms | 30ms | -3ms | -8.98
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createSchedulePost | p99 | 10ms | 0s | -10ms | -105.15
| getChannelMembers | p99 | 25ms | 0s | -25ms | -101.21
| updateReadStateAllThreadsByUser | p99 | 5ms | 0s | -5ms | -101.01
| updateChannelBookmark | p99 | 50ms | 0s | -50ms | -101.01
| followThreadByUser | p99 | 25ms | 0s | -25ms | -100.59
| setPostReminder | p99 | 90ms | 0s | -90ms | -100.56
| logout | p99 | 87ms | 0s | -87ms | -100.53
| deletePost | p99 | 49ms | 0s | -49ms | -100.51
| createCategoryForTeamForUser | p99 | 99ms | 0s | -99ms | -100.51
| getTeamStats | p99 | 50ms | 0s | -50ms | -100.50
| unfollowThreadByUser | p99 | 25ms | 0s | -25ms | -100.22
| createChannel | p99 | 486ms | 0s | -486ms | -100.03
| updateCategoriesForTeamForUser | p99 | 226ms | 0s | -226ms | -100.00
| createChannelBookmark | p99 | 93ms | 0s | -93ms | -99.47
| getTeamScheduledPosts | p99 | 21ms | 0s | -21ms | -98.04
| searchPostsInTeam | p99 | 1.336s | 239ms | -1.097s | -82.08
| removeUserCustomStatus | p99 | 422ms | 99ms | -323ms | -76.56
| getPostsForChannel | p99 | 202ms | 48ms | -154ms | -76.16
| searchGroupChannels | p99 | 22ms | 5ms | -17ms | -75.93
| getPreferences | p99 | 18ms | 5ms | -13ms | -74.00
| getThreadsForUser | p99 | 19ms | 5ms | -14ms | -72.00
| getAllTeams | p99 | 16ms | 5ms | -11ms | -69.65
| getChannelMembersForUser | p99 | 16ms | 5ms | -11ms | -69.58
| getTeamMembersForUser | p99 | 16ms | 5ms | -11ms | -69.57
| createGroupChannel | p99 | 800ms | 248ms | -552ms | -69.00
| getChannelsForTeamForUser | p99 | 16ms | 5ms | -11ms | -68.63
| getChannelMembersForTeamForUser | p99 | 15ms | 5ms | -10ms | -65.69
| getUsersByNames | p99 | 13ms | 5ms | -8ms | -63.81
| getDrafts | p99 | 19ms | 7ms | -12ms | -62.82
| getUsers | p99 | 18ms | 7ms | -11ms | -60.13
| getClientConfig | p99 | 24ms | 10ms | -14ms | -57.85
| getTeamsUnreadForUser | p99 | 23ms | 10ms | -13ms | -56.53
| deleteDraft | p99 | 17ms | 8ms | -9ms | -53.91
| upsertDraft | p99 | 21ms | 10ms | -11ms | -53.10
| getChannelsForUser | p99 | 10ms | 5ms | -5ms | -51.54
| getUser | p99 | 18ms | 9ms | -9ms | -49.74
| createDirectChannel | p99 | 491ms | 248ms | -243ms | -49.50
| getTeamMember | p99 | 10ms | 5ms | -5ms | -49.46
| updateReadStateThreadByUser | p99 | 99ms | 50ms | -49ms | -49.28
| addChannelMember | p99 | 480ms | 248ms | -232ms | -48.33
| getTeamsForUser | p99 | 10ms | 5ms | -5ms | -47.66
| createUser | p99 | 464ms | 245ms | -219ms | -47.23
| viewChannel | p99 | 44ms | 24ms | -20ms | -45.75
| getPostThread | p99 | 45ms | 25ms | -20ms | -44.30
| getCategoriesForTeamForUser | p99 | 42ms | 25ms | -17ms | -40.31
| createPost | p99 | 832ms | 498ms | -334ms | -40.17
| patchPost | p99 | 77ms | 50ms | -27ms | -35.29
| searchUsers | p99 | 73ms | 49ms | -24ms | -33.04
| saveReaction | p99 | 37ms | 25ms | -12ms | -32.47
| getPublicChannelsForTeam | p99 | 37ms | 25ms | -12ms | -32.12
| getChannelMember | p99 | 25ms | 18ms | -7ms | -27.78
| getChannel | p99 | 32ms | 24ms | -8ms | -24.95
| listChannelBookmarksForChannel | p99 | 10ms | 8ms | -2ms | -20.92
| updatePreferences | p99 | 25ms | 21ms | -4ms | -16.02
| getPostsForChannelAroundLastUnread | p99 | 50ms | 48ms | -2ms | -4.03
| getFileThumbnail | p99 | 91ms | 88ms | -3ms | -3.30
| addTeamMember | p99 | 998ms | 985ms | -13ms | -1.30
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 3ms | -1ms | -28.396
| |  P99| 20ms| 16ms | -4ms | -20.267
| BotStore.Get |  Avg| 4ms| 3ms | -1ms | -24.199
| |  P99| 42ms| 5ms | -37ms | -87.574
| ChannelBookmarkStore.Delete |  Avg| 5ms| 0s | -5ms | -102.988
| |  P99| 10ms| 0s | -10ms | -101.010
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -88.920
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.836
| ChannelBookmarkStore.Save |  Avg| 8ms| 0s | -8ms | -95.688
| |  P99| 24ms| 0s | -24ms | -99.377
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -61.725
| ChannelStore.Autocomplete |  Avg| 33ms| 30ms | -3ms | -9.044
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 46ms| 23ms | -23ms | -49.471
| |  P99| 96ms| 97ms | 1ms | 1.037
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 20ms | -1ms | -4.652
| |  P99| 62ms| 49ms | -13ms | -21.138
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 50ms| 45ms | -5ms | -10.087
| ChannelStore.CreateSidebarCategory |  Avg| 43ms| 0s | -43ms | -99.496
| |  P99| 99ms| 0s | -99ms | -100.508
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 5ms | -9ms | -63.387
| ChannelStore.GetAllChannelMembersForUser |  Avg| 4ms| 5ms | 1ms | 25.235
| |  P99| 29ms| 24ms | -5ms | -17.087
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 31ms | 19ms | 153.568
| |  P99| 96ms| 219ms | 123ms | 128.681
| ChannelStore.GetByName |  Avg| 4ms| 2ms | -2ms | -44.652
| |  P99| 35ms| 7ms | -28ms | -79.780
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.543
| ChannelStore.GetChannels |  Avg| 3ms| 2ms | -1ms | -39.526
| |  P99| 16ms| 5ms | -11ms | -69.760
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.853
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.928
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.341
| ChannelStore.GetGuestCount |  Avg| 3ms| 2ms | -1ms | -39.581
| |  P99| 17ms| 5ms | -12ms | -68.948
| ChannelStore.GetMember |  Avg| 3ms| 2ms | -1ms | -36.403
| |  P99| 18ms| 5ms | -13ms | -71.917
| ChannelStore.GetMemberCount |  Avg| 15ms| 11ms | -4ms | -25.854
| |  P99| 45ms| 25ms | -20ms | -44.354
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -51.256
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.489
| ChannelStore.GetMembers |  Avg| 8ms| 0s | -8ms | -97.048
| |  P99| 25ms| 0s | -25ms | -101.215
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 5ms | -10ms | -66.623
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 5ms | -11ms | -70.368
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.312
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 12ms | -1ms | -7.579
| |  P99| 37ms| 25ms | -12ms | -32.117
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 13ms| 12ms | -1ms | -7.634
| |  P99| 40ms| 25ms | -15ms | -37.145
| ChannelStore.GetSidebarCategory |  Avg| 8ms| 0s | -8ms | -97.192
| |  P99| 68ms| 0s | -68ms | -100.000
| ChannelStore.GetTeamChannels |  Avg| 14ms| 0s | -14ms | -103.638
| |  P99| 46ms| 0s | -46ms | -100.533
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -61.685
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 0s | -2ms | -96.409
| |  P99| 10ms| 0s | -10ms | -104.533
| ChannelStore.Save |  Avg| 11ms| 9ms | -2ms | -18.332
| |  P99| 45ms| 10ms | -35ms | -77.670
| ChannelStore.SaveMember |  Avg| 27ms| 24ms | -3ms | -11.267
| |  P99| 81ms| 49ms | -32ms | -39.374
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -76.015
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -59.435
| ChannelStore.UpdateSidebarCategories |  Avg| 38ms| 0s | -38ms | -99.574
| |  P99| 92ms| 0s | -92ms | -100.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.956
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -27.257
| |  P99| 25ms| 13ms | -12ms | -48.499
| CommandWebhookStore.Cleanup |  Avg| 2ms| 0s | -2ms | -100.550
| |  P99| 5ms| 0s | -5ms | -101.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 1ms| 0s | -1ms | -68.309
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 5ms | -10ms | -68.069
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 7ms| 0s | -7ms | -106.343
| |  P99| 46ms| 0s | -46ms | -99.459
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 5ms | -10ms | -66.589
| DraftStore.GetDraftsForUser |  Avg| 3ms| 2ms | -1ms | -35.066
| |  P99| 19ms| 5ms | -14ms | -75.313
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -72.296
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.559
| EmojiStore.GetMultipleByName |  Avg| 2ms| 0s | -2ms | -112.023
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -51.896
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.126
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.380
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.773
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 6ms | -17ms | -74.151
| FileInfoStore.SetContent |  Avg| 7ms| 6ms | -1ms | -13.726
| |  P99| 29ms| 10ms | -19ms | -66.376
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.288
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 5ms | -9ms | -64.350
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -56.033
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.755
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.095
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -37.855
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 5ms | -8ms | -63.745
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 5ms | -14ms | -74.567
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 29ms| 22ms | -7ms | -23.932
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.712
| LinkMetadataStore.Save |  Avg| 4ms| 3ms | -1ms | -27.962
| |  P99| 19ms| 5ms | -14ms | -73.684
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.290
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 5ms | -11ms | -70.064
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 10ms | -10ms | -49.604
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.083
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -35.077
| |  P99| 21ms| 9ms | -12ms | -57.601
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 2ms | 1ms | 68.387
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 5ms | -12ms | -69.164
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.228
| PostPriorityStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 47.894
| |  P99| 9ms| 22ms | 13ms | 146.397
| PostPriorityStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -34.240
| |  P99| 21ms| 9ms | -12ms | -56.406
| PostStore.AnalyticsPostCount |  Avg| 259ms| 0s | -259ms | -99.970
| |  P99| 498ms| 0s | -498ms | -100.101
| PostStore.Delete |  Avg| 15ms| 0s | -15ms | -101.976
| |  P99| 25ms| 0s | -25ms | -100.604
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -55.981
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -71.877
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.814
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.394
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 0s | -3ms | -103.048
| |  P99| 19ms| 0s | -19ms | -101.604
| PostStore.GetPostReminders |  Avg| 7ms| 6ms | -1ms | -13.669
| |  P99| 23ms| 10ms | -13ms | -55.437
| PostStore.GetPosts |  Avg| 3ms| 4ms | 1ms | 30.061
| |  P99| 15ms| 22ms | 7ms | 45.896
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.950
| PostStore.GetPostsBefore |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 18ms| 10ms | -8ms | -45.120
| PostStore.GetPostsByThread |  Avg| 5ms| 3ms | -2ms | -39.197
| |  P99| 23ms| 8ms | -15ms | -64.185
| PostStore.GetPostsSince |  Avg| 8ms| 5ms | -3ms | -36.005
| |  P99| 47ms| 24ms | -23ms | -48.921
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.352
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 11ms| 9ms | -2ms | -17.997
| |  P99| 47ms| 34ms | -13ms | -27.508
| PostStore.SearchPostsForUser |  Avg| 40ms| 24ms | -16ms | -39.754
| |  P99| 1.336s| 223ms | -1.113s | -83.282
| PostStore.SetPostReminder |  Avg| 6ms| 0s | -6ms | -93.319
| |  P99| 22ms| 0s | -22ms | -100.687
| PostStore.Update |  Avg| 12ms| 13ms | 1ms | 8.381
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 3ms| 0s | -3ms | -93.482
| |  P99| 23ms| 0s | -23ms | -101.099
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 5ms | -9ms | -64.530
| PreferenceStore.GetAll |  Avg| 3ms| 2ms | -1ms | -39.066
| |  P99| 17ms| 5ms | -12ms | -70.264
| PreferenceStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 35ms| 24ms | -11ms | -31.288
| ProductNoticesStore.ClearOldNotices |  Avg| 14ms| 0s | -14ms | -97.981
| |  P99| 25ms| 0s | -25ms | -100.597
| ProductNoticesStore.View |  Avg| 32ms| 25ms | -7ms | -22.023
| |  P99| 138ms| 50ms | -88ms | -63.993
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 30.873
| |  P99| 14ms| 10ms | -4ms | -29.319
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 3ms| 0s | -3ms | -107.963
| |  P99| 37ms| 5ms | -32ms | -85.333
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 0s | -3ms | -96.865
| |  P99| 8ms| 0s | -8ms | -106.665
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -100.990
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 4ms| 0s | -4ms | -112.303
| |  P99| 42ms| 0s | -42ms | -99.408
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 0s | -2ms | -90.307
| |  P99| 10ms| 0s | -10ms | -101.689
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 0s | -2ms | -88.696
| |  P99| 8ms| 0s | -8ms | -94.675
| SessionStore.Get |  Avg| 5ms| 4ms | -1ms | -21.272
| |  P99| 24ms| 10ms | -14ms | -57.632
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.572
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 3ms| 2ms | -1ms | -38.525
| |  P99| 13ms| 5ms | -8ms | -60.899
| SessionStore.Remove |  Avg| 3ms| 0s | -3ms | -104.221
| |  P99| 5ms| 0s | -5ms | -100.998
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 22ms| 11ms | -11ms | -49.317
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.696
| SharedChannelStore.HasChannel |  Avg| 2ms| 0s | -2ms | -102.921
| |  P99| 8ms| 0s | -8ms | -98.825
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.676
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 9ms | -8ms | -46.763
| StatusStore.SaveOrUpdate |  Avg| 16ms| 3ms | -13ms | -83.560
| |  P99| 376ms| 5ms | -371ms | -98.603
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 4ms | 1ms | 29.446
| |  P99| 20ms| 10ms | -10ms | -49.140
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -50.347
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.580
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.990
| TeamStore.GetActiveMemberCount |  Avg| 37ms| 0s | -37ms | -100.740
| |  P99| 50ms| 0s | -50ms | -100.503
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -54.391
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -53.046
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -53.362
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -48.365
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -59.575
| TeamStore.GetTotalMemberCount |  Avg| 37ms| 0s | -37ms | -100.934
| |  P99| 50ms| 0s | -50ms | -100.503
| TeamStore.SaveMember |  Avg| 24ms| 21ms | -3ms | -12.637
| |  P99| 56ms| 44ms | -12ms | -21.286
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -54.253
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.151
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 2ms | -1ms | -38.094
| |  P99| 13ms| 5ms | -8ms | -60.802
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.254
| ThreadStore.GetThreadForUser |  Avg| 6ms| 4ms | -2ms | -35.682
| |  P99| 25ms| 10ms | -15ms | -61.145
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 3ms | -3ms | -51.864
| |  P99| 24ms| 7ms | -17ms | -69.429
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 3ms | -1ms | -27.388
| |  P99| 19ms| 5ms | -14ms | -74.697
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -53.601
| ThreadStore.GetTotalUnreadMentions |  Avg| 3ms| 2ms | -1ms | -38.706
| |  P99| 16ms| 5ms | -11ms | -67.507
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -54.372
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 3ms| 2ms | -1ms | -39.950
| |  P99| 12ms| 5ms | -7ms | -57.215
| ThreadStore.MaintainMembership |  Avg| 6ms| 5ms | -1ms | -16.963
| |  P99| 22ms| 10ms | -12ms | -53.448
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.299
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 0s | -4ms | -112.752
| |  P99| 5ms| 0s | -5ms | -101.010
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.086
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.462
| TokenStore.Cleanup |  Avg| 2ms| 0s | -2ms | -101.120
| |  P99| 5ms| 0s | -5ms | -101.005
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 0s | -2ms | -102.616
| |  P99| 5ms| 0s | -5ms | -100.992
| UserStore.AutocompleteUsersInChannel |  Avg| 38ms| 34ms | -4ms | -10.638
| |  P99| 139ms| 222ms | 83ms | 59.619
| UserStore.Count |  Avg| 10ms| 8ms | -2ms | -19.909
| |  P99| 25ms| 10ms | -15ms | -60.545
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.498
| UserStore.GetAllProfiles |  Avg| 3ms| 2ms | -1ms | -38.354
| |  P99| 11ms| 5ms | -6ms | -56.677
| UserStore.GetAllProfilesInChannel |  Avg| 155ms| 119ms | -36ms | -23.241
| |  P99| 474ms| 248ms | -226ms | -47.632
| UserStore.GetByUsername |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.161
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 5ms | -6ms | -53.219
| UserStore.GetMany |  Avg| 2ms| 0s | -2ms | -95.477
| |  P99| 7ms| 0s | -7ms | -103.704
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 5ms | -10ms | -66.737
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 2ms | -1ms | -39.486
| |  P99| 12ms| 5ms | -7ms | -59.569
| UserStore.GetProfilesInChannel |  Avg| 20ms| 0s | -20ms | -99.279
| |  P99| 236ms| 0s | -236ms | -100.106
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 0s | -4ms | -94.666
| |  P99| 5ms| 0s | -5ms | -100.995
| UserStore.GetUnreadCount |  Avg| 3ms| 2ms | -1ms | -30.707
| |  P99| 19ms| 9ms | -10ms | -51.999
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.829
| UserStore.Save |  Avg| 69ms| 66ms | -3ms | -4.335
| |  P99| 175ms| 100ms | -75ms | -42.811
| UserStore.Search |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 69ms| 49ms | -20ms | -29.013
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -38.400
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 3ms | -1ms | -26.684
| |  P99| 21ms| 7ms | -14ms | -65.966
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -41.397
| UserStore.UpdateUpdateAt |  Avg| 5ms| 4ms | -1ms | -21.969
| |  P99| 18ms| 10ms | -8ms | -43.906
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -48.949
| WebhookStore.GetOutgoingByTeam |  Avg| 5ms| 2ms | -3ms | -61.016
| |  P99| 38ms| 5ms | -33ms | -86.299
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 179ms| 105ms | -74ms | -41.334
| | P99| 480ms| 248ms | -232ms | -48.326
| addTeamMember | Avg| 552ms| 477ms | -75ms | -13.587
| | P99| 998ms| 985ms | -13ms | -1.302
| autocompleteChannelsForTeamForSearch | Avg| 47ms| 23ms | -24ms | -51.559
| | P99| 96ms| 97ms | 1ms | 1.037
| autocompleteUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 108ms| 217ms | 109ms | 100.687
| createCategoryForTeamForUser | Avg| 45ms| 0s | -45ms | -99.758
| | P99| 99ms| 0s | -99ms | -100.508
| createChannel | Avg| 191ms| 0s | -191ms | -99.814
| | P99| 486ms| 0s | -486ms | -100.034
| createChannelBookmark | Avg| 22ms| 0s | -22ms | -98.325
| | P99| 93ms| 0s | -93ms | -99.466
| createDirectChannel | Avg| 200ms| 106ms | -94ms | -47.042
| | P99| 491ms| 248ms | -243ms | -49.499
| createGroupChannel | Avg| 306ms| 167ms | -139ms | -45.424
| | P99| 800ms| 248ms | -552ms | -69.000
| createPost | Avg| 203ms| 429ms | 226ms | 111.409
| | P99| 832ms| 498ms | -334ms | -40.166
| createSchedulePost | Avg| 3ms| 0s | -3ms | -85.976
| | P99| 10ms| 0s | -10ms | -105.150
| createUser | Avg| 142ms| 99ms | -43ms | -30.353
| | P99| 464ms| 245ms | -219ms | -47.232
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 8ms | -9ms | -53.910
| deletePost | Avg| 23ms| 0s | -23ms | -101.465
| | P99| 49ms| 0s | -49ms | -100.513
| followThreadByUser | Avg| 13ms| 0s | -13ms | -101.876
| | P99| 25ms| 0s | -25ms | -100.591
| getAllTeams | Avg| 3ms| 2ms | -1ms | -37.750
| | P99| 16ms| 5ms | -11ms | -69.652
| getCategoriesForTeamForUser | Avg| 14ms| 12ms | -2ms | -14.721
| | P99| 42ms| 25ms | -17ms | -40.311
| getChannel | Avg| 5ms| 9ms | 4ms | 78.198
| | P99| 32ms| 24ms | -8ms | -24.951
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 25ms| 18ms | -7ms | -27.778
| getChannelMembers | Avg| 9ms| 0s | -9ms | -103.509
| | P99| 25ms| 0s | -25ms | -101.215
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 5ms | -10ms | -65.693
| getChannelMembersForUser | Avg| 4ms| 3ms | -1ms | -28.359
| | P99| 16ms| 5ms | -11ms | -69.584
| getChannelStats | Avg| 2ms| 4ms | 2ms | 94.632
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 3ms | 1ms | 44.334
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 3ms| 2ms | -1ms | -38.113
| | P99| 16ms| 5ms | -11ms | -68.629
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -51.535
| getClientConfig | Avg| 6ms| 5ms | -1ms | -17.059
| | P99| 24ms| 10ms | -14ms | -57.855
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 7ms | -12ms | -62.821
| getFilePreview | Avg| 39ms| 38ms | -1ms | -2.579
| | P99| 96ms| 95ms | -1ms | -1.042
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 91ms| 88ms | -3ms | -3.297
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 45ms| 25ms | -20ms | -44.296
| getPostsForChannel | Avg| 23ms| 11ms | -12ms | -52.213
| | P99| 202ms| 48ms | -154ms | -76.162
| getPostsForChannelAroundLastUnread | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 50ms| 48ms | -2ms | -4.035
| getPreferences | Avg| 3ms| 2ms | -1ms | -37.604
| | P99| 18ms| 5ms | -13ms | -73.998
| getProfileImage | Avg| 66ms| 104ms | 38ms | 57.988
| | P99| 249ms| 470ms | 221ms | 88.614
| getPublicChannelsForTeam | Avg| 14ms| 13ms | -1ms | -7.060
| | P99| 37ms| 25ms | -12ms | -32.117
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -49.460
| getTeamMembersForUser | Avg| 3ms| 2ms | -1ms | -37.570
| | P99| 16ms| 5ms | -11ms | -69.574
| getTeamScheduledPosts | Avg| 5ms| 0s | -5ms | -109.279
| | P99| 21ms| 0s | -21ms | -98.036
| getTeamStats | Avg| 37ms| 0s | -37ms | -100.199
| | P99| 50ms| 0s | -50ms | -100.503
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -47.661
| getTeamsUnreadForUser | Avg| 4ms| 3ms | -1ms | -22.361
| | P99| 23ms| 10ms | -13ms | -56.533
| getThreadsForUser | Avg| 4ms| 2ms | -2ms | -54.635
| | P99| 19ms| 5ms | -14ms | -72.005
| getUser | Avg| 3ms| 2ms | -1ms | -38.210
| | P99| 18ms| 9ms | -9ms | -49.744
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 1ms | -2ms | -63.604
| | P99| 18ms| 7ms | -11ms | -60.135
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 2ms | -1ms | -37.355
| | P99| 13ms| 5ms | -8ms | -63.813
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 8ms | -2ms | -20.920
| login | Avg| 66ms| 69ms | 3ms | 4.572
| | P99| 243ms| 246ms | 3ms | 1.235
| logout | Avg| 30ms| 0s | -30ms | -98.634
| | P99| 87ms| 0s | -87ms | -100.533
| patchPost | Avg| 25ms| 26ms | 1ms | 3.983
| | P99| 77ms| 50ms | -27ms | -35.294
| removeUserCustomStatus | Avg| 138ms| 33ms | -105ms | -76.231
| | P99| 422ms| 99ms | -323ms | -76.563
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 10ms | 1ms | 10.875
| | P99| 37ms| 25ms | -12ms | -32.467
| searchAllChannels | Avg| 33ms| 30ms | -3ms | -8.983
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 3ms | -1ms | -28.343
| | P99| 22ms| 5ms | -17ms | -75.934
| searchPostsInTeam | Avg| 47ms| 36ms | -11ms | -23.371
| | P99| 1.336s| 239ms | -1.097s | -82.084
| searchUsers | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 73ms| 49ms | -24ms | -33.042
| setPostReminder | Avg| 20ms| 0s | -20ms | -102.050
| | P99| 90ms| 0s | -90ms | -100.559
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 0s | -13ms | -97.847
| | P99| 25ms| 0s | -25ms | -100.216
| updateCategoriesForTeamForUser | Avg| 57ms| 0s | -57ms | -99.538
| | P99| 226ms| 0s | -226ms | -100.000
| updateChannelBookmark | Avg| 26ms| 0s | -26ms | -100.570
| | P99| 50ms| 0s | -50ms | -101.009
| updatePreferences | Avg| 9ms| 8ms | -1ms | -11.575
| | P99| 25ms| 21ms | -4ms | -16.015
| updateReadStateAllThreadsByUser | Avg| 4ms| 0s | -4ms | -110.517
| | P99| 5ms| 0s | -5ms | -101.010
| updateReadStateThreadByUser | Avg| 37ms| 29ms | -8ms | -21.363
| | P99| 99ms| 50ms | -49ms | -49.276
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 401ms| 481ms | 80ms | 19.949
| | P99| 986ms| 990ms | 4ms | 0.406
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 10ms | -11ms | -53.103
| viewChannel | Avg| 12ms| 8ms | -4ms | -34.618
| | P99| 44ms| 24ms | -20ms | -45.751
